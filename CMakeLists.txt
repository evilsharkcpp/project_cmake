cmake_minimum_required(VERSION 3.10)

project(project_cmake)

set(CXX_STANDARD 11)
set(CXX_STANDARD_REQUIRED true)

option(TESTS on)

add_subdirectory(projects)

if(TESTS)
    enable_testing()
    add_subdirectory(tests)
endif()