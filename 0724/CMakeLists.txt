cmake_minimum_required(VERSION 2.8.3)
PROJECT(helloworld)
MESSAGE(STATUS "BINARY DIRECTORY ${PROJECT_BINARY_DIR}")  
MESSAGE(STATUS "SOURCE DIRECTORY" ${PROJECT_SOURCE_DIR})

add_subdirectory(src)

add_subdirectory(src_bin)
