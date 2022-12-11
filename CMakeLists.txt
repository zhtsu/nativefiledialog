cmake_minimum_required(VERSION 3.16)
project(nativefiledialog)

add_library(
    nativefiledialog
    SHARED
    src/nfd_common.c
    src/nfd_win.cpp
)
target_include_directories(nativefiledialog PUBLIC src/include)
