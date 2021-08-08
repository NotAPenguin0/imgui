cmake_minimum_required(VERSION 3.16 FATAL_ERROR)

project(imgui CXX)

add_library(imgui STATIC "src/imgui.cpp" "src/imgui_draw.cpp" "src/imgui_widgets.cpp" "src/imgui_tables.cpp")

target_include_directories(imgui PUBLIC "${CMAKE_CURRENT_SOURCE_DIR}/include")
