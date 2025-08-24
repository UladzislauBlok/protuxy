cmake_minimum_required(VERSION 4.1)
project(protuxy)

set(CMAKE_CXX_STANDARD 23)

include_directories(src)

set(SRC_DIR src)

add_executable(protuxy ${SRC_DIR}/main.cpp)
