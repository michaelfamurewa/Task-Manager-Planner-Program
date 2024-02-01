cmake_minimum_required(VERSION 3.25)
project(Task_manager)

set(CMAKE_CXX_STANDARD 17)

add_executable(Task_manager main.cpp taskClass.h taskClass.cpp linkedList.h linkedList.cpp Functions.h Functions.cpp)
