cmake_minimum_required(VERSION 2.8)
project(prediction)
find_package(OpenCV REQUIRED)
include_directories(${OpenCV_INCLUDE_DIRS})
add_executable(prediction prediction.cpp)
target_link_libraries(prediction ${OpenCV_LIBS})

