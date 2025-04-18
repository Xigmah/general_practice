cmake_minimum_required(VERSION 3.10.0)
project(helloworld VERSION 0.1.0 LANGUAGES C CXX)

set(SOURCES 
    hello_world.cpp
    hello_world.h)
add_executable(${PROJECT_NAME} ${SOURCES})
