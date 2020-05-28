cmake_minimum_required(VERSION 3.10.2)

file(GLOB SRC_FILES *.cpp)

add_library(dir1839 SHARED ${SRC_FILES} )
add_subdirectory(dir1840)
add_subdirectory(dir1873)
add_subdirectory(dir2043)
add_subdirectory(dir2183)
add_subdirectory(dir2370)
set_source_files_properties(file2487.cpp PROPERTIES COMPILE_FLAGS -Dfile2487)
