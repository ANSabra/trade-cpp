cmake_minimum_required(VERSION 3.22.0)
project(trade-cpp VERSION 0.1.0)

find_package(Boost REQUIRED)

add_executable(trade-cpp src/main.cpp)
target_include_directories(trade-cpp PRIVATE ${Boost_INCLUDE_DIR})
