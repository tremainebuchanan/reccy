# reccy
C++ file watcher written using Nodejs without dependencies (yet) for Linux users.
# Why reccy
The library was built to automate the generation of C++ object files when writing .cpp programs. Generating `.o` files was a problem for me as I would need to run the following lines of code over and over again:

`g++ -o output_file_name source_file.cpp`

then run `./output_file_name` to execute the program.

This library would reduce the need to type and run the `g++` command manually.

# Requirements

1. `nodejs` must be installed on your laptop
2. `g++` must be installed on your laptop

# Usage
The library currently runs on Linux.

From the terminal run the following 

`npm install -g reccy` or

`npm i -g reccy`
 
 Once installed navigate to the folder containing `.cpp` files. 

 On the command line within the folder containing the `.cpp` files type

 `reccy <filename>.cpp`

 An object file `.o` with the same name as the `.cpp` file will be created. 

# TODO 
   
1. Check if `g++` is installed in host machine before executing script. 
2. Execute `.o` file provided that a flag is passed to `reccy`.
3. Create unit tests
4. Add functionality to watch more than one `.cpp` files.


