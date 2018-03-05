cmake_minimum_required(VERSION 3.9)
project(3_HelloWorld3)

set(CMAKE_CXX_STANDARD 11)

aux_source_directory(. sourceList)

add_executable(3_HelloWorld3 ${sourceList})