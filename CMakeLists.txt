cmake_minimum_required(VERSION 3.18)
project(lzf LANGUAGES C)

add_library(lzf "${CMAKE_CURRENT_SOURCE_DIR}/src/lzf_c.c" "${CMAKE_CURRENT_SOURCE_DIR}/src/lzf_d.c")

target_include_directories(lzf PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/include)
