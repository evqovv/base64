cmake_minimum_required(VERSION 3.10.0)
project(base64 VERSION 0.1.0 LANGUAGES C CXX)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++23")

include_directories($ENV{HOME}/fast_io/include)

set(CMAKE_EXPORT_COMPILE_COMMANDS ON)

add_executable(base64 main.cpp)