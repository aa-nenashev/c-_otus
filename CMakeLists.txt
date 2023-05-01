cmake_minimum_required(VERSION 3.10)

set(PATCH_VERSION "1" CACHE INTERNAL "Patch version")
set(PROJECT_VESRION 0.0.${PATCH_VERSION})

project(otus_course VERSION ${PROJECT_VESRION})
find_package(GTest REQUIRED)
enable_testing()

add_subdirectory(task_1)