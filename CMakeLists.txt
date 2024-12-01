cmake_minimum_required(VERSION 3.25)
project(RayTracingInOneWeekend)
set(CMAKE_CXX_STANDARD 26)

set(SOURCE_FILES main.cpp)

add_executable(raytracing ${SOURCE_FILES})