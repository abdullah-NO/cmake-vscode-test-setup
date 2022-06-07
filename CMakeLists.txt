cmake_minimum_required(VERSION 3.2)

set(CMAKE_CXX_STANDARD 17)
project(helloBro LANGUAGES CXX)
message(STATUS "compiler is used from the path: ${CMAKE_CXX_COMPILER}")

add_library(hell STATIC src/helloworld.cpp)
target_include_directories(hell PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/include)


add_executable(helloBro main.cpp)
target_link_libraries(helloBro PUBLIC hell)


 