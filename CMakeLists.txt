cmake_minimum_required(VERSION 2.8)
set(CMAKE_CXX_STANDARD 11)
project(cpp-cmake-circle-ci)

set(EXECUTABLE_OUTPUT_PATH ${CMAKE_SOURCE_DIR}/bin)
add_executable(point_test ${PROJECT_SOURCE_DIR}/src/Test.cpp)