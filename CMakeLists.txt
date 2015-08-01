cmake_minimum_required (VERSION 2.6)
project ("Hello World")

add_executable (hello hello.c)
install (TARGETS hello DESTINATION bin)
