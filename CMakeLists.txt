cmake_minimum_required(VERSION 3.21)
project(review C)

set(CMAKE_C_STANDARD 99)

add_executable(review main.c)

add_executable(hello review01/hello.c)
