###############################################################################
# SUBDIRECTORIES
###############################################################################

add_subdirectory(formatters)

###############################################################################
# FILES
###############################################################################

INSTALL(DIRECTORY ${CMAKE_CURRENT_SOURCE_DIR} DESTINATION include FILES_MATCHING PATTERN "*.hpp")
