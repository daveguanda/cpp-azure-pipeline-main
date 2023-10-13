add_library(my_lib my_lib.cpp)
target_include_directories(my_lib PUBLIC include)

install(TARGETS my_lib
 RUNTIME DESTINATION bin
 LIBRARY DESTINATION lib
 ARCHIVE DESTINATION lib)