cmake_minimum_required(VERSION 3.28)
set(CMAKE_CXX_STANDARD 23)
project(vrg_entry_demo)

add_executable(vrg_entry_demo src/main.cpp)
target_include_directories(vrg_entry_demo PRIVATE external)
