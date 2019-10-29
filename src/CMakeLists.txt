cmake_minimum_required(VERSION 2.8)

project(hello_world)

set(SOURCE_EXE main.cpp)

include_directories(foo)

add_executable(main ${SOURCE_EXE})

add_subdirectory(foo)

target_link_libraries(main foo)
