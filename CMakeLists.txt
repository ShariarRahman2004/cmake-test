cmake_minimum_required(VERSION 3.10..3.15)

project(test LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

include_directories(include)

add_executable(test src/main.cpp src/utils.cpp)
