cmake_minimum_required(VERSION 3.9)
project(HelloWorld5)

set(CMAKE_CXX_STANDARD 11)

ADD_SUBDIRECTORY(src bin)

INSTALL(TARGETS build/bin/HelloWorld RUNTIME DESTINATION bin)
#INSTALL(PROGRAMS run.sh DESTINATION bin)

