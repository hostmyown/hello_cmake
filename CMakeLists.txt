cmake_minimum_required(VERSION 3.0)

project(hello_cmake
    VERSION 1.0
    DESCRIPTION "Hello CMake"
    LANGUAGES C)

add_executable(hello_cmake src/main.c)
