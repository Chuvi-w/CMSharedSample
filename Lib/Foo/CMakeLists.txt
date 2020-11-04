add_library(Foo SHARED Foo.cpp Foo.h)
target_link_libraries(Foo PUBLIC Bar)
target_include_directories(Foo PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})