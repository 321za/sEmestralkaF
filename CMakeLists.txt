cmake_minimum_required(VERSION 3.18)
project(sEmestralkaF C)

set(CMAKE_C_STANDARD 99)

add_executable(sEmestralkaF main.c)
add_executable(server server.c)
add_executable(client client.c)