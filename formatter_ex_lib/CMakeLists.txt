add_library(formatter_ex_lib STATIC
    formatter_ex.cpp
    formatter_ex.h
)

target_include_directories(formatter_ex_lib
    PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}
)

target_link_libraries(formatter_ex_lib
    PRIVATE formatter_lib
)
