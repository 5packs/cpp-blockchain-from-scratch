cmake_minimum_required(VERSION 3.15)

project(cpp-blockchain VERSION 1.0)

# Set C++ standard
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

# Create executable
add_executable(${PROJECT_NAME} src/main.cpp)
