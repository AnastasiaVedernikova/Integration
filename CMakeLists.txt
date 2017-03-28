cmake_minimum_required(VERSION 3.6)
project(C)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES main.cpp)
add_executable(C ${SOURCE_FILES})

TARGET_LINK_LIBRARIES( C pthread)