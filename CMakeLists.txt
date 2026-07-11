cmake_minimum_required(VERSION 3.22)
project(mira_colorcodes_lib LANGUAGES C)

set(MIRA_COLORCODES_VERSION "1.0.0")

add_library(mira_colorcodes_lib INTERFACE)

target_include_directories(mira_colorcodes_lib INTERFACE
    $<BUILD_INTERFACE:${CMAKE_CURRENT_SOURCE_DIR}/include>
)