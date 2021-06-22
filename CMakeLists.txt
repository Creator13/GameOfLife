cmake_minimum_required(VERSION 3.19)
project(GameOfLife)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(GameOfLife
        GameOfLife.cpp
        GameOfLife.h
        gameOfLife_main.cpp
        Grid.cpp
        Grid.h
        RuleSet.h
        StandardRuleSet.cpp
        StandardRuleSet.h)
