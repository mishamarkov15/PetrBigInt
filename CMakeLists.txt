cmake_minimum_required(VERSION 3.24)
project(PetrBigInt)

set(CMAKE_CXX_STANDARD 20)

add_executable(PetrBigInt main.cpp bigint.inc.cpp)
