cmake_minimum_required(VERSION 2.8)

project(foo)

set(SOURCE_LIB foo.cpp)

add_library(foo STATIC ${SOURCE_LIB})
