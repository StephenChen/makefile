cmake_minimum_required(VERSION 3.20)
project(makefile)

set(CMAKE_C_STANDARD 99)

add_executable(makefile main.c defs.h command.h buffer.h kbd.c display.c insert.c search.c files.c utils.c command.c)
