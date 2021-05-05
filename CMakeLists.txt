cmake_minimum_required(VERSION 3.4)
project(cpp-vorlesung)
set(CMAKE_CXX_STANDARD 17)

include(cmake/Conan.cmake)
run_conan()

include(cmake/CompilerWarnings.cmake)


add_subdirectory(libs)
add_subdirectory(app)