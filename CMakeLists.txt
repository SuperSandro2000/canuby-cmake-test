cmake_minimum_required (VERSION 3.10)

project(cmake-test)

add_library(math src/math.cc)

add_executable(cmake-test src/main.cc)
target_link_libraries(cmake-test math)
