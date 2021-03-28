cmake_minimum_required(VERSION 3.16.0)

project(cmake-cpp-stater VERSION 1.0.0 LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

set(SRCS
    src/main.cpp
)

add_executable(demo ${SRCS})