cmake_minimum_required(VERSION 3.26)
project(epoll_ltet)

set(CMAKE_CXX_STANDARD 11)

include_directories(/usr/local/include)
include_directories(/usr/include)
link_directories(/usr/local/lib)
link_directories(/usr/lib)
link_directories(/usr/lib64)

add_executable(epoll_ltet main.cpp)
