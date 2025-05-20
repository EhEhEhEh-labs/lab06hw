add_executable(solver_app
    equation.cpp
)

target_link_libraries(solver_app
    PRIVATE formatter_ex_lib
    PRIVATE solver_lib
)
