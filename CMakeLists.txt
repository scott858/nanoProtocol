cmake_minimum_required(VERSION 3.7)
project(aeroProtocol)

set(CMAKE_C_STANDARD 11)

set(SOURCE_FILES main.c)
add_executable(aeroProtocol ${SOURCE_FILES})
target_link_libraries(aeroProtocol /usr/local/lib/libnanomsg.so)
