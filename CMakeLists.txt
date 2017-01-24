cmake_minimum_required(VERSION 2.9)
project(HolaWorld)

file(GLOB C_FILES "HolaWorld.c")
add_executable(HolaWorld ${C_FILES})

install(TARGETS HolaWorld RUNTIME DESTINATION bin)
