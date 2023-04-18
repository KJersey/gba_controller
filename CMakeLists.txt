cmake_minimum_required(VERSION 3.24.2)
project(gba_controller)
set(CMAKE_CC_STANDARD 17)

set(SOURCE_FILES src/main.c)

add_executable(gba_controller ${SOURCE_FILES})