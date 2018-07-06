# simcpp  
This is simple c++ compiling script for unix and unix-like environment.  
Simcpp uses gcc to compile and vim to edit and create projects.  
Syntax: `simcpp [OPTION] CPP_PROJECT_NAME`.

There are four options:  
-`simcpp -e [program_name]` will edit the cpp source code.   
-`simcpp -c [program_name]` will compile the cpp source code.   
-`simcpp -p [program_name]` will compile the cpp source code using C++11 standard.   
-`simcpp -x [program_name]` will execute the cpp bin file.   

This program at the moment can only execute programs that has been placed in its directory. No house directory housekeeping has been introduced
