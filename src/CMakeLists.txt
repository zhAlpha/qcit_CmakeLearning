#cmake_minimum_required (vresion 2.8.3)
#project(hello)

include_directories(../include)

set(HEADERS ../include/hello.h)

set(SOURCE_FILES hello.cpp)

set(LIBRARY_OUTPUT_PATH ${PROJECT_SOURCE_DIR}/lib)

add_library(hello_shared SHARED ${HEADERS} ${SOURCE_FILES})

#add_library(hello_STATIC STATIC ${HEADERS} ${SOURCE_FILES})
