cmake_minimum_required(VERSION 3.9)
project(ML)

set(CMAKE_CXX_STANDARD 11)

add_subdirectory(../../../dlib-19.9/dlib dlib_build)
add_executable(ML main.cpp)
add_executable(source ../../../dlib-19.9/dlib/all/source.cpp)