cmake_minimum_required(VERSION 3.9)
project(HelloWorld5)

set(CMAKE_CXX_STANDARD 11)

ADD_SUBDIRECTORY(src temp)

INSTALL(PROGRAMS run.sh DESTINATION bin)




