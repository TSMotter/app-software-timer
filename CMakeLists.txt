cmake_minimum_required (VERSION 3.14)
project (app-software-timer VERSION 0.1 DESCRIPTION "Stand alone app that uses the software-timer")

add_executable(example main.c)
target_link_libraries(example PRIVATE gm_timer)
