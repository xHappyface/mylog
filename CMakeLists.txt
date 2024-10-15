cmake_minimum_required(VERSION 3.29.0 FATAL_ERROR)
project(mylog)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

set(
    SOURCES
    main.cpp
)

add_executable(${PROJECT_NAME} ${SOURCES})