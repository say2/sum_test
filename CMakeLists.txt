cmake_minimum_required(VERSION 3.8)
project(sum_test)

set(CMAKE_C_STANDARD 99)

set(SOURCE_FILES main.cpp cmake-build-debug/sum.h sum.cpp)
add_executable(sum_test ${SOURCE_FILES})