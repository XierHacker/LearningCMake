cmake_minimum_required(VERSION 3.9)
project(HelloWord2)

set(CMAKE_CXX_STANDARD 11)


aux_source_directory(. source_list)

add_executable(HelloWord2 ${source_list})
