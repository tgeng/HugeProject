cmake_minimum_required(VERSION 3.10.2)

file(GLOB SRC_FILES *.cpp)

add_library(dir40616 SHARED ${SRC_FILES} )
set_source_files_properties(file40617.cpp PROPERTIES COMPILE_FLAGS -Dfile40617)
