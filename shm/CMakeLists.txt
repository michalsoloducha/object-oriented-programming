cmake_minimum_required(VERSION 3.0.0)

set(CMAKE_CXX_STANDARD 20)

project(shmProject)

add_executable(${PROJECT_NAME} main.cpp Cargo.cpp Island.cpp Map.cpp Player.cpp Ship.cpp)

