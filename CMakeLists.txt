cmake_minimum_required(VERSION 2.8.0)

#project name
project(KALMANFILTER)

list(APPEND CMAKE_MODULE_PATH "${CMAKE_SOURCE_DIR}/cmake/modules")
include(cmake/BuildType.cmake)

#where things go during compiling
set(KALMANFILTER_INSTALL_LIB_DIR lib)

set(EXECUTABLE_OUTPUT_PATH "${CMAKE_BINARY_DIR}/bin")
set(LIBRARY_OUTPUT_PATH "${CMAKE_BINARY_DIR}/lib")

#declare options -- test, measure and confirm
option(BUILD_SHARED_LIBS "Build KalmanFilter with shared libraries." ON)

find_package(Eigen3 REQUIRED)

#where the action is at -- build the project
add_subdirectory(src)




