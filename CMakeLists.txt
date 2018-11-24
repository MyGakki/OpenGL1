cmake_minimum_required(VERSION 3.8)
project(OpenGL1)

set(CMAKE_CXX_STANDARD 11)

include_directories(C:/Users/HopePower/Documents/GLUT)
add_executable(OpenGL1 main.cpp)

set(TARGET_LIB "C:/Users/HopePower/Documents/GLUT/glut.h"
        "C:/Users/HopePower/Documents/GLUT/glut32.lib")

target_link_libraries(OpenGL1 ${TARGET_LIB} -lopengl32  -lglu32)