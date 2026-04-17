cmake_minimum_required(VERSION 3.10)

project(sprint1-calculator VERSION 1.0.0 LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(calculator 
    main.cpp
    calculator.cpp
    calculator.h
    calculator_ui.h
    calculator_ui.cpp
)