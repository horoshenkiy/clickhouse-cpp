ADD_LIBRARY (gtest-lib STATIC
    src/gtest-all.cc
)

TARGET_INCLUDE_DIRECTORIES(gtest-lib PUBLIC include)
