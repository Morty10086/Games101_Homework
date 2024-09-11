cmake_minimum_required (VERSION 2.8.11)
project (Transformation)

find_package(Eigen3 REQUIRED PATHS /E:/Graphics/eigen-3.4.0)
include_directories(EIGEN3_INCLUDE_DIR)

add_executable (Transformation main.cpp)
