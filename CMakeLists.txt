cmake_minimum_required(VERSION 3.3.0)

project(abc-library-cmake)

# add ABC to project
add_subdirectory(abc EXCLUDE_FROM_ALL)

# add the demo program, and link with the ABC library
add_executable(demo abc/src/demo.c)
target_link_libraries(demo libabc)

# run the program
enable_testing()
add_test(NAME run-demo COMMAND demo ${CMAKE_SOURCE_DIR}/abc/i10.aig)
