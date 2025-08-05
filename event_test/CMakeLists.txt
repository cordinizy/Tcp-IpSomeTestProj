cmake_minimum_required(VERSION 3.26)
project(event_test)

set(CMAKE_CXX_STANDARD 11)

include_directories(/usr/local/include)
include_directories(/usr/include)
include_directories(/usr/src/kernels/3.10.0-693.el7.x86_64.debug/include)
link_directories(/usr/local/lib)
link_directories(/usr/lib)
link_directories(/usr/lib64)

add_executable(event_test main.cpp)
