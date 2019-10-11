cmake_minimum_required (VERSION 2.6)
project (Counter)
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wall -O0 -fprofile-arcs -ftest-coverage")
add_executable(counter counter.c)
