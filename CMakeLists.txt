cmake_minimum_required(VERSION 3.29)
project(Final_Project)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(Final_Project
    Car.h
    Formula1.h
    main.cpp
    MotorEspecial.h
    SUV.h)
