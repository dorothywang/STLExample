cmake_minimum_required(VERSION 3.0)

SET(EVN_GCC C:/msys64/mingw64/bin)
SET(CMAKE_C_COMPILER ${EVN_GCC}/gcc.exe)
SET(CMAKE_CXX_COMPILER C:/msys64/mingw64/bin/g++.exe)

set(CMAKE_BUILD_TYPE Debug)
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++14")

project(moveSemantic)

add_executable(moveSemantic
	testMove.cpp
)
