# reccy
C++ file watcher written using Nodejs without dependencies (yet) for Linux users.
# Why Reccy
The library was built to automate the generation of C++ object files when writing .cpp programs. Generating `.o` files was a problem for me as I would need to run the following lines of code over and over again:

`g++ -o output_file_name source_file.cpp`

then run `./output_file_name` to execute the program.

This library would reduce the need to type and run the `g++` command manually.

#Requirements

1. `nodejs` must be installed on your laptop
2. `g++` must be installed on your laptop

# Usage
The library currently runs on Linux.

To run the library,

 

The script will create a `build` folder where the object file will be generated. 

# TODO 
   
1. Add ability to pass more arguments to script i.e. `--no-build` which signifies that no build folder should be created.
2. Check if `g++` is installed in host machine.
3. Create unit tests
4. Add functionality to watch more than one `.cpp` files.
5. Package and submit for inclusion on https://www.npmjs.com/

