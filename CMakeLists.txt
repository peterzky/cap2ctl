cmake_minimum_required(VERSION 3.0)

project(cap2ctl)

add_executable(cap2ctl cap2ctl.c)
target_compile_options(cap2ctl PRIVATE -Wall -Wextra)

install(TARGETS cap2ctl RUNTIME DESTINATION bin)
