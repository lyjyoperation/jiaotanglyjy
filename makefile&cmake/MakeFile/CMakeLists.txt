cmake_minimum_required(VERSION 3.0)

project(hello)

set(EXECUTABLE_OUTPUT_PATH ${PROJECT_SOURCE_DIR}/bin)

file(GLOB SOURCES "${PROJECT_SOURCE_DIR}/*.c")

include_directories("${PROJECT_SOURCE_DIR}/include")

add_executable(hello ${SOURCES})
