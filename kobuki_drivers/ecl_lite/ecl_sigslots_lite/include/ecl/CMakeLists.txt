##############################################################################
# Subdirectories
##############################################################################

add_subdirectory(sigslots_lite)

##############################################################################
# Files
##############################################################################

INSTALL(DIRECTORY ${CMAKE_CURRENT_SOURCE_DIR} DESTINATION include FILES_MATCHING PATTERN "*.hpp")
