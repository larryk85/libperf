cmake_minimum_required(VERSION 3.8)
set(VERSION_MAJOR 1)
set(VERSION_MINOR 0)
set(VERSION_PATCH 0)
set(VERSION_SUFFIX rc1)
project(libperf VERSION ${VERSION_MAJOR}.${VERSION_MINOR}.${VERSION_PATCH})

add_library(libperf ${CMAKE_CURRENT_SOURCE_DIR}/src/libperf.c)
