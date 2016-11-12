cmake_minimum_required(VERSION 3.1)

aux_source_directory(./src SRC)

add_executable(dirtos ${SRC} src/main.cpp)
