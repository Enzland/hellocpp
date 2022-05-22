cmake_minimum_required(VERSION 3.10)

project(hello VERSION 1.0)
add_executable(hello main.cpp src/Blah.cpp)

target_include_directories(hello PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/include)

