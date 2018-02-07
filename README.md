turtlebot_ros2_navigation
========================================================================================
Considering that there is no available navigation stack in ROS2 for the time being and 
this project is trying to explore and research the solution to bridge the ROS2 navigation
from ROS navigation stack. The purpose is to run all the components in ROS2 except for 
move_base in ROS for this ROS2 bridge navigation solution. 

Generally, it should be something like the following:

# ROS2
* ROS2 Core
* ROS2 enabling to the core drivers of the kobuki
* Kobuki control system of chassis in turtlebot2
* 3D camera
* SLAM with cartographer 
* map_server and amcl
* rviz2

# ROS
* move_base
* roscore
