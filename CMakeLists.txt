cmake_minimum_required(VERSION 2.8 FATAL_ERROR)

project(ply_downsampler)

find_package(PCL 1.2 REQUIRED)

include_directories(${PCL_INCLUDE_DIRS})
link_directories(${PCL_LIBRARY_DIRS})
add_definitions(${PCL_DEFINITIONS})

add_executable (ply_downsampler ply_downsampler.cpp)
target_link_libraries (ply_downsampler ${PCL_LIBRARIES})
