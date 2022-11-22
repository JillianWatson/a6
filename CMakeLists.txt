cmake_minimum_required(VERSION 3.15)

project(RS)

set(CMAKE_C_STANDARD 11)
set(CMAKE_C_FLAGS "-Wall -Wextra")

add_executable(rs rs.c)
