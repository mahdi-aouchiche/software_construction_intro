# Software Construction: Introduction

Author: Mahdi Aouchiche (<https://github.com/mahdi-aouchiche/software_construction_1_intro>)

* Intro to good practices in software construction using C++ programming language in a Linux environment.
* Create header directory for header files ".hpp": each class has its own .hpp file.
* Create src directory for source files ".cpp": all source code files for each class in a separate ".cpp" file and a at least 1 program to run which includes a main function.
* Introduction to CMake as a build system built on top of GNU's make and supports advanced features to build projects:
  * Create a CMakeLists.txt file which CMake system looks for to know what to build for the project.
  * Create a build directory where to run "cmake -S . -B build" as Linux terminal command to build the project.
  * Run the Linux command "cmake --build build/" to execute the Makefile generated by CMake and create the executable programs of the project.

## To run the project nicely run the following commands:

```c++
cmake -S . -B build
cmake --build build/
```

## 3 executables are created, use one of the commands to run an executable:

```c++
./build/hello_world
./build/area_calculator
./build/standard_area_calculator

```
