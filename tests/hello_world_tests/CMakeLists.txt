include_directories(${PROJECT_SOURCE_DIR}/projects/hello_world/include)

add_executable(hello_world_tests hwt.cpp)
target_link_libraries(hello_world_tests PUBLIC hello_world)
#target_link_directories(hello_world_tests PUBLIC ${PROJECT_BINARY_DIR}/projects/hello_world)