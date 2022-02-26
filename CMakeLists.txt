cmake_minimum_required(VERSION 3.13)
project(Kaos)
set(CMAKE_CXX_STANDARD 20)

set(SOURCES
	src/main.cpp
)

add_executable(Kaos ${SOURCES})