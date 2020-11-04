# learn_cmake
my_project is the first cmake project. It has a standard folder structure of division and addition operations of a calculator.
I've created CMakeLists.txt.
add_executable() is and standard cmake functions where 1st name(calculator) rest all are dependencies.

Execution steps:
Inside my_project folder, mkdir build_dir;cd build_dir; cmake ..; make; ./calculator

In commit, Added sub-folder for target my_math & my_print. Created their CMakeLists.txt.
CMake file is being created inside each target and target_include_directories() is added to directly fetch header files from src files.
