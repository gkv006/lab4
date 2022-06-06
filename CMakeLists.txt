cmake_minimum_required(VERSION 3.22)
project(lab4)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(lab4
        main.cpp
        Student.h
        test.h
        tree.h)
