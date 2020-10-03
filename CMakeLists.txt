cmake_minimum_required(VERSION 2.8.4)

project(POISSON_RECON)
set(CMAKE_MODULE_PATH ${CMAKE_MODULE_PATH}
    "${CMAKE_SOURCE_DIR}/cmake/Modules/")

find_package(OpenMP REQUIRED)

set(CMAKE_VERBOSE_MAKEFILE on)

set(LIBRARY_OUTPUT_PATH ${CMAKE_BINARY_DIR}/lib)
add_subdirectory(src)