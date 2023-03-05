cmake_minimum_required(VERSION 3.22)
project(simple_chat_ui C)

set(CMAKE_C_STANDARD 17)

add_executable(simple_chat_ui main.c)
target_link_libraries(simple_chat_ui ncurses)
