cmake_minimum_required(VERSION 3.10)
project(network_project)
file(GLOB source_files CONFIGURE_DEPENDS 
	"*.h"
	"*.cpp"
	"src/Classes/*/*/*.cpp"
	"src/Classes/*/*/*.h"
	)
add_executable(network_project ${source_files})
set(CMAKE_CXX_STANDAR 11)
set(CMAKE_CXX_STANDAR_REQUIRED True)
