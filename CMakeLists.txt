cmake_minimum_required(VERSION 3.10)
project(lab03)

# Общие настройки для всех проектов
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_ARCHIVE_OUTPUT_DIRECTORY ${CMAKE_BINARY_DIR}/lib)
set(CMAKE_LIBRARY_OUTPUT_DIRECTORY ${CMAKE_BINARY_DIR}/lib)
set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_BINARY_DIR}/bin)

# Добавляем поддиректории с библиотеками и приложениями
add_subdirectory(formatter_lib)
add_subdirectory(solver_lib)
add_subdirectory(formatter_ex_lib)
add_subdirectory(hello_world_application)
add_subdirectory(solver_application)
