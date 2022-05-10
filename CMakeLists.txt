cmake_minimum_required(VERSION 3.10)

project(
    AppExample
    VERSION 0.1
    DESCRIPTION "Example Application using a library"
    LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 11)
enable_testing()

add_subdirectory(src)
add_subdirectory(thirdparty/cmake-example-library EXCLUDE_FROM_ALL)
