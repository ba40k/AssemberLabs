cmake_minimum_required(VERSION 3.29)
project(BugGameLabyrinthGenerator)

set(CMAKE_CXX_STANDARD 20)

add_executable(generator main.cpp)
include_directories(spdlog/include)
add_subdirectory(Google_tests)


