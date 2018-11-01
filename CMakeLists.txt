cmake_minimum_required(VERSION 3.0)
find_package(pixel REQUIRED)
set(CMAKE_CXX_STANDARD 17)

add_executable(colors colors.cpp)
target_link_libraries(colors pixel::pixel)
