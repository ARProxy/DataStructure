cmake_minimum_required(VERSION 3.30)
project(C)

set(CMAKE_CXX_STANDARD 20)

add_executable(C main.cpp
        LinkedList.cpp
        linkedList/LinkedList.h
        LinkedList.cu
        LinkedList.cuh)
