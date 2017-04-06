cmake_minimum_required(VERSION 3.5)

project(first)

set(CMAKE_C_FLAGS_DEBUG "-O0 -ggdb")
set(CMAKE_C_FLAGS_RELEASE "-Os")

add_executable(first main.c)
