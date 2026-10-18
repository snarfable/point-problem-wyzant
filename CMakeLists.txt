cmake_minimum_required(VERSION 3.10)

project(problem VERSION 1.0)

add_executable(problem problem.cpp)
target_compile_options(problem PRIVATE -std=c++20)