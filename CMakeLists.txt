cmake_minimum_required(VERSION 3.16)

project(hello_world)

add_executable(app main.cpp)

install(TARGETS app DESTINATION bin)


