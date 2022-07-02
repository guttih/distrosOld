cmake_minimum_required(VERSION 3.14)


set(This cppTests)

project(${This})

# GoogleTest requires at least C++14
set(CMAKE_CXX_STANDARD 14)

include(FetchContent)
FetchContent_Declare(
  googletest
  URL https://github.com/google/googletest/archive/609281088cfefc76f9d0ce82e1ff6c30cc3591e5.zip
)
# For Windows: Prevent overriding the parent project's compiler/linker settings
set(gtest_force_shared_crt ON CACHE BOOL "" FORCE)
FetchContent_MakeAvailable(googletest)

enable_testing()

add_executable(
    ${This}
    ${This}.cc
)
target_link_libraries(
    ${This}
  gtest_main
)

include(GoogleTest)
gtest_discover_tests(${This})

# Now do the following in the same directory as this file is in
# 1. create a file called XXX.cc and add the following content to it: 
#     // File: XXX.cc
#     #include <gtest/gtest.h>
#     // Demonstrate some basic assertions.
#     TEST(HelloTest, BasicAssertions) {
#       // Expect two strings not to be equal.
#       EXPECT_STRNE("hello", "world");
#       // Expect equality.
#       EXPECT_EQ(7 * 6, 42);
#     }
#
# 2. Run these commands
#     cmake -S . -B build
#     cmake --build build