cmake_minimum_required(VERSION 2.6)
project(aboutcpp)

add_executable(01-data-types 01-data-types)

install(TARGETS 01-data-types RUNTIME DESTINATION bin)
