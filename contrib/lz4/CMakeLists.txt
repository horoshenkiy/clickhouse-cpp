ADD_LIBRARY (lz4-lib STATIC
    src/lz4.c
    src/lz4hc.c
)

TARGET_INCLUDE_DIRECTORIES(lz4-lib PUBLIC include)

set_property(TARGET lz4-lib PROPERTY POSITION_INDEPENDENT_CODE ON)
