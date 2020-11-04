cmake_minimum_required( VERSION 3.10 )

set ( CMAKE_WINDOWS_EXPORT_ALL_SYMBOLS ON )
if(NOT WIN32 AND NOT MSVC)
	message(FATAL_ERROR "This sample is created for question aboud debugging targets with SHARED LIBRARY dependencies in Visual Studio. Please, use Visual Studio to reproduce it.")
endif()
project(CMSharedSample)

add_subdirectory(Lib)
add_subdirectory(Baz)
