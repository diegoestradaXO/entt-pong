cmake_minimum_required(VERSION 3.23.2)

project(NewProject VERSION 1.0)

add_executable(NewProject src/main.cpp)

set (CMAKE_CXX_FLAGS "-F/Library/Frameworks -framework SDL2 -framework SDL2_image -std=c++20")