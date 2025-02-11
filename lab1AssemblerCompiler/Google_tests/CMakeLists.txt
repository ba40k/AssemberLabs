project(Google_tests)

add_subdirectory(lib)
enable_testing()
include_directories(${gtest_SOURCE_DIR}/include ${gtest_SOURCE_DIR})



add_test(runUnitTests Google_Tests_run)