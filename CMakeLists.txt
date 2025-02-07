cmake_minimum_required(VERSION 3.18)
project(sattva)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSIONS OFF)

include_directories(src)
set(SOURCES 
    src/main.cpp
    )

add_executable(sattva ${SOURCES})