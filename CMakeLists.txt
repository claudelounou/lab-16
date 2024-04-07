cmake_minimum_required(VERSION 3.26)
project(Lab16_16.0 C)

set(CMAKE_C_STANDARD 11)

add_library(Lab16
        libs/data_structures/matrix/matrix.c
        libs/data_structures/matrix/matrix.h
        libs/util/util.c
        libs/util/util.h
        main.c
        solution.c)

add_subdirectory(libs)

target_link_libraries(data_structures)
