add_definitions(-DBSDIFF_EXECUTABLE -DBSPATCH_EXECUTABLE)
add_executable(bsdiff bsdiff.c)
target_link_libraries(bsdiff bz2)
add_executable(bspatch bspatch.c)
target_link_libraries(bspatch bz2)
