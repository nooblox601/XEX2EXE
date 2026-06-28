cmake_minimum_required(VERSION 3.20)

project(XEX2EXE)

set(CMAKE_CXX_STANDARD 20)

file(GLOB_RECURSE SOURCES CONFIGURE_DEPENDS
    "*.cpp"
)

add_executable(XEX2EXE ${SOURCES})
