cmake_minimum_required(VERSION 3.14)
project(Molecule VERSION 1.0
	             DESCRIPTION "A class to represent molecules"
		         LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED TRUE)

# Include directories
include_directories(mol_exe include)

# Add executable
add_executable(mol_exe src/main.cpp src/molecule.cpp)
