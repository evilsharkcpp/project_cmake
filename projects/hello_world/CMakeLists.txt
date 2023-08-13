include_directories(include)

if(TESTS)
    add_library(hello_world STATIC bsearch.cpp)
else()
    add_executable(hello_world hello_world.cpp)
endif()