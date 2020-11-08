cmake_minimum_required(VERSION 3.0.0)

find_package(my_math)

if(my_math_FOUND)
	message("my_math lib found")
	add_executable(calc main.cpp)
	target_link_libraries(calc my_math)
else()
	message("my_math lib not found")
endif()
