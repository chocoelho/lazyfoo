cmake_minimum_required(VERSION 3.15)
project(lazyfoo)

set(CMAKE_CXX_STANDARD 14)

SET(CMAKE_CXX_LINK_FLAGS "-lSDL2")

add_executable(lazyfoo main.cpp)