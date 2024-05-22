cmake_minimum_required(VERSION 3.10)

# Project name and version
project(Main VERSION 1.0)

# Specify the C++ standard
set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED True)

# Include directories
include_directories(include)

# Add the executable
add_executable(${PROJECT_NAME} src/main.cpp)