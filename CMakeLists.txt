cmake_minimum_required(VERSION 3.10..3.15)

project(test LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_EXPORT_COMPILE_COMMANDS ON)

include_directories(include)

add_executable(test src/main.cpp src/utils.cpp src/helper.cpp)
