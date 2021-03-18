cmake_minimum_required(VERSION 3.5)

project(cmaketest)

add_executable(helloWorld main.cpp)

set_target_properties(
    helloWorld PROPERTIES
    CXX_STANDARD 11
    CXX_STANDARD_REQUIRED ON
)