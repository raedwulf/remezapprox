cmake_minimum_required(VERSION 2.8)

set(CMAKE_MODULE_PATH ${CMAKE_SOURCE_DIR}/cmake)

project(REMEZAPPROX)
set(PROJECT_NAME "remezapprox")

find_package(Boost REQUIRED)
find_package(NTL REQUIRED)
include_directories(${Boost_INCLUDE_DIR})
add_executable(remezapprox main.cpp f.cpp)
target_link_libraries(remezapprox ${NTL_LIBRARY})

install(TARGETS remezapprox DESTINATION bin)
