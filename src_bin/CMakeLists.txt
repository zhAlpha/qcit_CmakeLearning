include_directories(../include)

set(EXECUTABLE_OUTPUT_PATH ${PROJECT_SOURCE_DIR}/bin)
#set(EXECUTABLE_OUTPUT_PATH ../../bin)
add_executable(hello1 usehello.cpp)

target_link_libraries(hello1 hello_shared)
