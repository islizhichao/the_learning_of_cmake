# The minimum version of CMake that we need
cmake_minimum_required( VERSION 3.5 )

# The name of this project
project( hello_cmake )

# Generate a executable file
add_executable( ${PROJECT_NAME} main.cpp )