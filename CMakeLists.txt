cmake_minimum_required(VERSION 3.26)
project(depg0213_epd C)

set(CMAKE_C_STANDARD 11)

include_directories(.)

add_library(depg0213_epd depg0213_epd.c)
