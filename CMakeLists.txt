cmake_minimum_required(VERSION 3.20)

project(26SOC0790_C_CPP_Programming
    VERSION 0.1.0
    LANGUAGES C CXX
)

set(CMAKE_C_STANDARD 17)
set(CMAKE_C_STANDARD_REQUIRED ON)
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(26soc0790
    src/main.cpp
)

target_include_directories(26soc0790 PRIVATE
    ${CMAKE_CURRENT_SOURCE_DIR}/include
)
