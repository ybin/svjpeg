cmake_minimum_required(VERSION 3.13)
project(svjpeg)

set(CMAKE_CXX_STANDARD 14)

include_directories(${CMAKE_CURRENT_LIST_DIR})

add_executable(svjpeg test.cpp)
