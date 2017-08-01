project(ppp_chapter_02)
cmake_minimum_required(VERSION 2.8)

include_directories("../../include/")
set(CMAKE_CXX_STANDARD 14)

add_executable(minimal src/minimal.cpp)
add_executable(hello_world src/hello_world.cpp)
