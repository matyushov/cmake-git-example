cmake_minimum_required(VERSION 3.15)

project(CmakeExample)

file(GLOB SOURCE "main.cpp")

add_executable(cmake-example ${SOURCE})
