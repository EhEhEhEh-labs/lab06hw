add_library(formatter_lib STATIC
    formatter.cpp
    formatter.h
)

target_include_directories(formatter_lib
    PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}
)
