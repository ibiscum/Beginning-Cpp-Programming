cmake_minimum_required(VERSION 3.20)
project(Beginning_Cpp_Programming)

set(CMAKE_CXX_STANDARD 17)

add_subdirectory(Chapter01)
add_subdirectory(Chapter02)
add_subdirectory(Chapter03)
add_subdirectory(Chapter04)
add_subdirectory(Chapter05)
add_subdirectory(Chapter06)
add_subdirectory(Chapter07)
add_subdirectory(Chapter08)
add_subdirectory(Chapter09)


add_executable(ch02 Chapter02/calc.cpp)

add_executable(ch03 Chapter03/hexdump.cpp)

add_executable(ch04 Chapter04/tasks.cpp)

add_executable(ch05 Chapter05/files.cpp)

add_executable(ch06 Chapter06/search.cpp)

add_executable(ch07 Chapter07/team_builder.cpp)

add_executable(ch08 Chapter08/csv_parser.cpp)

add_executable(ch09 Chapter09/email_parser.cpp)