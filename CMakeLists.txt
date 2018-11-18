cmake_minimum_required(VERSION 3.0 FATAL_ERROR)

project(redis VERSION 3.0)

set(EXAMPLE
	linenoise.c example.c
)

add_executable(example ${EXAMPLE})

