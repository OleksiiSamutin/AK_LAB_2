cmake_minimum_required(VERSION 3.16.3)

project("AK_LAB_2" VERSION 0.1.0)

add_library(mycalc STATIC calculator.cpp)
add_executable("${PROJECT_NAME}" main.cpp)
target_link_libraries("${PROJECT_NAME}" mycalc)
