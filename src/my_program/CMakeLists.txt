add_executable(my_program main.cpp)
target_link_libraries(my_program PRIVATE my_lib)

install(TARGETS my_program RUNTIME DESTINATION bin)
