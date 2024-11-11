cmake_minimum_required(VERSION 3.29)
project(Calculator C)

set(CMAKE_C_STANDARD 11)

add_executable(Calculator main.c tinyexpr.c)

target_include_directories(Calculator PRIVATE ${CMAKE_SOURCE_DIR})

