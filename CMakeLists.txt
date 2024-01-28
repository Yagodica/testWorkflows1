cmake_minimum_required(VERSION 3.10)

project(my_project)

set(CMAKE_SYSTEM_NAME Linux)
set(CMAKE_C_COMPILER gcc)
set(CMAKE_CXX_COMPILER g++)

add_executable(my_program main.cpp)
