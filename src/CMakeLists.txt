add_library(hell STATIC helloworld.cpp)
target_include_directories(hell PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/../include)