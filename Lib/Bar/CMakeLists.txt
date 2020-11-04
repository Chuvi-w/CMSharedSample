
add_library(Bar SHARED Bar.cpp Bar.h)
target_include_directories(Bar PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})