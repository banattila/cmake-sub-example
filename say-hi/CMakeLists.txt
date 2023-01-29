add_library(
    say-hi
    src/say-hi/hello.hpp
    src/say-hi/hello.cpp
)

target_include_directories(say-hi PUBLIC "${CMAKE_CURRENT_SOURCE_DIR}/src")