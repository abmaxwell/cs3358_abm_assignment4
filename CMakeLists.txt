cmake_minimum_required(VERSION 3.8)
project(cs3358_abm_assignment4)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        sequence.template
        sequence.h
        sequenceTest.cpp)

add_executable(cs3358_abm_assignment4 ${SOURCE_FILES})