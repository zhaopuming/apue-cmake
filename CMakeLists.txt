cmake_minimum_required (VERSION 2.6)
project (apue)

include_directories (".")

find_library (APUE apue "lib")

add_subdirectory ("ch01")
