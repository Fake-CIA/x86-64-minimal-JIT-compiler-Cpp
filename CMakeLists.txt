cmake_minimum_required(VERSION 3.1)

project(x86-64-minimal-JIT-compiler-Cpp VERSION 1.0)

# To debug cmakelists
set(CMAKE_VERBOSE_MAKEFILE FALSE)

set(CMAKE_CXX_STANDARD 14)
set(CMAKE_CXX_STANDARD_REQUIRED True)

add_compile_options(-Wall -pedantic)

add_subdirectory(part_1)
add_subdirectory(part_2)