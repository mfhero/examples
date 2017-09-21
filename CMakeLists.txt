project('example')
cmake_minimum_required(VERSION 2.0)

add_compile_options(-std=c++11)
add_compile_options(-O3)

include_directories(include/)

add_library(functions SHARED src/functions.cpp)

add_executable(hello src/hello.cpp)
