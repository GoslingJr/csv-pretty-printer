cmake_minimum_required(VERSION 3.10)
project(csv_pretty_printer C)

set(CMAKE_C_STANDARD 11)

add_executable(csv_printer
    src/main.c
    src/csv.c
)

enable_testing()
add_subdirectory(tests)
