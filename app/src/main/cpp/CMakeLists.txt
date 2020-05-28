# For more information about using CMake with Android Studio, read the
# documentation: https://d.android.com/studio/projects/add-native-code.html

# Sets the minimum version of CMake required to build the native library.

cmake_minimum_required(VERSION 3.10.2)

# Declares and names the project.

project("hugeproject")

# Creates and names a library, sets it as either STATIC
# or SHARED, and provides the relative paths to its source code.
# You can define multiple libraries, and CMake builds them for you.
# Gradle automatically packages shared libraries with your APK.

file(GLOB SRC_FILES *.cpp)

add_library( # Sets the name of the library.
             native-lib

             # Sets the library as a shared library.
             SHARED

             # Provides a relative path to your source file(s).
             ${SRC_FILES} )
add_subdirectory(dir0)
add_subdirectory(dir385)
add_subdirectory(dir405)
add_subdirectory(dir521)
add_subdirectory(dir7941)
add_subdirectory(dir35201)
add_subdirectory(dir35251)
add_subdirectory(dir35435)
add_subdirectory(dir40735)
add_subdirectory(dir41110)
set_source_files_properties(file41158.cpp PROPERTIES COMPILE_FLAGS -Dfile41158)

set_source_files_properties(file41159.cpp PROPERTIES COMPILE_FLAGS -Dfile41159)

set_source_files_properties(file41160.cpp PROPERTIES COMPILE_FLAGS -Dfile41160)

set_source_files_properties(file41161.cpp PROPERTIES COMPILE_FLAGS -Dfile41161)

set_source_files_properties(file41162.cpp PROPERTIES COMPILE_FLAGS -Dfile41162)

set_source_files_properties(file41163.cpp PROPERTIES COMPILE_FLAGS -Dfile41163)

set_source_files_properties(file41164.cpp PROPERTIES COMPILE_FLAGS -Dfile41164)

set_source_files_properties(file41165.cpp PROPERTIES COMPILE_FLAGS -Dfile41165)

set_source_files_properties(file41166.cpp PROPERTIES COMPILE_FLAGS -Dfile41166)

set_source_files_properties(file41167.cpp PROPERTIES COMPILE_FLAGS -Dfile41167)

set_source_files_properties(file41168.cpp PROPERTIES COMPILE_FLAGS -Dfile41168)

set_source_files_properties(file41169.cpp PROPERTIES COMPILE_FLAGS -Dfile41169)

set_source_files_properties(file41170.cpp PROPERTIES COMPILE_FLAGS -Dfile41170)

set_source_files_properties(file41171.cpp PROPERTIES COMPILE_FLAGS -Dfile41171)

set_source_files_properties(file41172.cpp PROPERTIES COMPILE_FLAGS -Dfile41172)

set_source_files_properties(file41173.cpp PROPERTIES COMPILE_FLAGS -Dfile41173)

set_source_files_properties(file41174.cpp PROPERTIES COMPILE_FLAGS -Dfile41174)

set_source_files_properties(file41175.cpp PROPERTIES COMPILE_FLAGS -Dfile41175)

set_source_files_properties(file41176.cpp PROPERTIES COMPILE_FLAGS -Dfile41176)

set_source_files_properties(file41177.cpp PROPERTIES COMPILE_FLAGS -Dfile41177)

set_source_files_properties(file41178.cpp PROPERTIES COMPILE_FLAGS -Dfile41178)

set_source_files_properties(file41179.cpp PROPERTIES COMPILE_FLAGS -Dfile41179)

set_source_files_properties(file41180.cpp PROPERTIES COMPILE_FLAGS -Dfile41180)

set_source_files_properties(file41181.cpp PROPERTIES COMPILE_FLAGS -Dfile41181)

set_source_files_properties(file41182.cpp PROPERTIES COMPILE_FLAGS -Dfile41182)

set_source_files_properties(file41183.cpp PROPERTIES COMPILE_FLAGS -Dfile41183)

set_source_files_properties(file41184.cpp PROPERTIES COMPILE_FLAGS -Dfile41184)

set_source_files_properties(file41185.cpp PROPERTIES COMPILE_FLAGS -Dfile41185)

set_source_files_properties(file41186.cpp PROPERTIES COMPILE_FLAGS -Dfile41186)

set_source_files_properties(file41187.cpp PROPERTIES COMPILE_FLAGS -Dfile41187)

set_source_files_properties(file41188.cpp PROPERTIES COMPILE_FLAGS -Dfile41188)

set_source_files_properties(file41189.cpp PROPERTIES COMPILE_FLAGS -Dfile41189)

set_source_files_properties(file41190.cpp PROPERTIES COMPILE_FLAGS -Dfile41190)

set_source_files_properties(file41191.cpp PROPERTIES COMPILE_FLAGS -Dfile41191)

set_source_files_properties(file41192.cpp PROPERTIES COMPILE_FLAGS -Dfile41192)

set_source_files_properties(file41193.cpp PROPERTIES COMPILE_FLAGS -Dfile41193)

set_source_files_properties(file41194.cpp PROPERTIES COMPILE_FLAGS -Dfile41194)

set_source_files_properties(file41195.cpp PROPERTIES COMPILE_FLAGS -Dfile41195)

set_source_files_properties(file41196.cpp PROPERTIES COMPILE_FLAGS -Dfile41196)

set_source_files_properties(file41197.cpp PROPERTIES COMPILE_FLAGS -Dfile41197)

set_source_files_properties(file41198.cpp PROPERTIES COMPILE_FLAGS -Dfile41198)

set_source_files_properties(file41199.cpp PROPERTIES COMPILE_FLAGS -Dfile41199)

set_source_files_properties(file41200.cpp PROPERTIES COMPILE_FLAGS -Dfile41200)

set_source_files_properties(file41201.cpp PROPERTIES COMPILE_FLAGS -Dfile41201)

set_source_files_properties(file41202.cpp PROPERTIES COMPILE_FLAGS -Dfile41202)

set_source_files_properties(file41203.cpp PROPERTIES COMPILE_FLAGS -Dfile41203)

set_source_files_properties(file41204.cpp PROPERTIES COMPILE_FLAGS -Dfile41204)

set_source_files_properties(file41205.cpp PROPERTIES COMPILE_FLAGS -Dfile41205)

set_source_files_properties(file41206.cpp PROPERTIES COMPILE_FLAGS -Dfile41206)

set_source_files_properties(file41207.cpp PROPERTIES COMPILE_FLAGS -Dfile41207)

set_source_files_properties(file41208.cpp PROPERTIES COMPILE_FLAGS -Dfile41208)

set_source_files_properties(file41209.cpp PROPERTIES COMPILE_FLAGS -Dfile41209)

set_source_files_properties(file41210.cpp PROPERTIES COMPILE_FLAGS -Dfile41210)

set_source_files_properties(file41211.cpp PROPERTIES COMPILE_FLAGS -Dfile41211)

set_source_files_properties(file41212.cpp PROPERTIES COMPILE_FLAGS -Dfile41212)

set_source_files_properties(file41213.cpp PROPERTIES COMPILE_FLAGS -Dfile41213)

set_source_files_properties(file41214.cpp PROPERTIES COMPILE_FLAGS -Dfile41214)

set_source_files_properties(file41215.cpp PROPERTIES COMPILE_FLAGS -Dfile41215)

set_source_files_properties(file41216.cpp PROPERTIES COMPILE_FLAGS -Dfile41216)

set_source_files_properties(file41217.cpp PROPERTIES COMPILE_FLAGS -Dfile41217)

set_source_files_properties(file41218.cpp PROPERTIES COMPILE_FLAGS -Dfile41218)

set_source_files_properties(file41219.cpp PROPERTIES COMPILE_FLAGS -Dfile41219)
