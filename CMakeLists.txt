cmake_minimum_required(VERSION 3.26)

project(shin)

add_executable(shin main.cpp)

install(TARGETS shin DESTINATION bin)

