cmake_minimum_required(VERSION 3.16)
set(CMAKE_CXX_STANDARD 20)
set(BUILD_SHARED_LIBS true)


project(test)
add_library(test main.c)
