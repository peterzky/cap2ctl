cmake_minimum_required(VERSION 3.0)

project(caps2esc)

add_executable(caps2ctl caps2ctl.c)
target_compile_options(caps2ctl PRIVATE -Wall -Wextra)

install(TARGETS caps2ctl RUNTIME DESTINATION bin)
