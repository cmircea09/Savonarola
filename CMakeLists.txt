cmake_minimum_required(VERSION 3.0.0)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(main src/main.cpp src/glad.c)

target_link_libraries(main ${PROJECT_SOURCE_DIR}/thirdparty/lib/glfw3.lib)