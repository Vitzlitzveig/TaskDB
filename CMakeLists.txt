cmake_minimum_required(VERSION 3.5)

project(TaskDB LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

set(sources "TTaskDB.h" "TTaskDB.cpp")

add_executable(${PROJECT_NAME} "main.cpp" ${sources})
