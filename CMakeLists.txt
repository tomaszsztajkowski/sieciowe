cmake_minimum_required(VERSION 3.21)
project(sieciowe)

set(CMAKE_CXX_STANDARD 14)

add_executable(client client.cpp)
add_executable(server server.cpp)