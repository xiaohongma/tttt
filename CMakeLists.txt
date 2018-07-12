cmake_minimum_required(VERSION 2.6)
project(testgit)

add_executable(testgit main.cpp)

install(TARGETS testgit RUNTIME DESTINATION bin)
