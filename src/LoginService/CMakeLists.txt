CMAKE_MINIMUM_REQUIRED( VERSION 2.8 )

PROJECT( Login_Service)

# Gather sources and headers.
FILE( GLOB_RECURSE LOGIN_SERVICE_SOURCES ${CMAKE_CURRENT_SOURCE_DIR}/*.cc )
FILE( GLOB_RECURSE LOGIN_SERVICE_HEADERS ${CMAKE_CURRENT_SOURCE_DIR}/*.h )

ADD_EXECUTABLE( login_service ${LOGIN_SERVICE_SOURCES} ${LOGIN_SERVICE_HEADERS} )