cmake_minimum_required(VERSION 2.8)

project(hello-world)

add_executable(hello-world hello-world.cpp)

install (TARGETS hello-world DESTINATION bin)
