cmake_minimum_required(VERSION 3.5)

project(OpenGL_tutorial_01)

set(CMAKE_CXX_FLAGS "-Wall -O3 -fpermissive -fopenmp -std=c++11")

include_directories(${CMAKE_SOURCE_DIR}/glad/include)

link_directories(/usr/local/lib)

add_executable(main main.cpp ./glad/src/glad.c)

target_link_libraries(main glfw3 GL X11 pthread Xrandr Xxf86vm Xinerama Xcursor Xi dl)