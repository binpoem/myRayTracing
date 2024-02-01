cmake_minimum_required(VERSION 3.22)

project(raytracing)

add_executable(inOneWeekend main.cc)

find_package(OpenMP REQUIRED)
target_link_libraries(inOneWeekend
  PUBLIC
      OpenMP::OpenMP_CXX
 )