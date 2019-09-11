

project(DemokltTracker)

cmake_minimum_required(VERSION 3.15)

find_package(VISP REQUIRED)
include_directories(${VISP_INCLUDE_DIRS})
add_executable(DemokltTracker DemokltTracker.cpp)
target_link_libraries(DemokltTracker ${VISP_LIBRARIES})
