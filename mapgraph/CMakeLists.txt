cmake_minimum_required(VERSION 3.27)
project(mapgraph)

file(GLOB SOURCE_FILES
    "src/*.cc")

add_executable(${PROJECT_NAME} ${SOURCE_FILES})