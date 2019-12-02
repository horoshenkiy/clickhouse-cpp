ADD_LIBRARY (cityhash-lib STATIC
    src/city.cc
)

TARGET_INCLUDE_DIRECTORIES(cityhash-lib PUBLIC include)

set_property(TARGET cityhash-lib PROPERTY POSITION_INDEPENDENT_CODE ON)
