cmake_minimum_required(VERSION 3.2)

set(CMAKE_CXX_STANDARD 17)
project(helloBro LANGUAGES CXX)

message(STATUS "compiler is used from the path: ${CMAKE_CXX_COMPILER}")
add_executable(helloBro main.cpp)


 