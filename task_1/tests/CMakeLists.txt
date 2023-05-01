add_executable(test_version test_package_version.cpp)
target_link_libraries(test_version PRIVATE GTest::GTest hello_world)

add_test(tests_version test_version)