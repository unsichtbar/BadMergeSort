cmake_minimum_required(VERSION 2.8.4)
project(example)

set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wall")

set(SOURCE_FILES main.c)
add_executable(dbsg ${SOURCE_FILES})