cmake_minimum_required(VERSION 3.15)
project(Program)

include_directories(glad) 

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_FLAGS "-lGL -lGLEW -lglfw")


add_executable(hello-Glfw 
	src/main.cpp 
	glad/glad.c 
)