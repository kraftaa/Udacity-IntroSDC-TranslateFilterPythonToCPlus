cmake_minimum_required(VERSION 3.10)
project(project)

set(CMAKE_CXX_STANDARD 11)

add_executable(project debugging_helpers.cpp helpers.cpp localizer.cpp simulate.cpp tests.cpp helpers.h debugging_helpers.h simulate.h tests.h localizer.h)