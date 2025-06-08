cmake_minimum_required (VERSION 3.14)
project (softim-standa-alone VERSION 0.1 DESCRIPTION "Stand alone app")

add_executable(example main.c)
target_link_libraries(example PRIVATE gm_timer)