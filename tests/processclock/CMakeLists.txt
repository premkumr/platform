ADD_EXECUTABLE(platform-processclock-test processclock_test.cc)
TARGET_LINK_LIBRARIES(platform-processclock-test gtest_main platform)
ADD_TEST(platform-gettimeofday-test platform-processclock-test)
