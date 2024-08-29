# Introduction
## What even is this project?

This is visual debugger that allows to step through the program execution and look into memory and CPU internals in the process


# Building
## Existing build script
That what I would suggest to use, it just build everything for you.

### available flags:
+ --alternative         - this one is used for building alternative solutions. It is used to get experimental results usually
+ --build               - this one is used for building (by default it only generate cmake stuff)
+ --test                - this one invokes tests
+ --verbose             - this one makes all the events in code beign printed to console
+ --output_dir=<name>   - this one takes argument (name of the folder) and build everything in this folder. By deafult it is set to "build" 

## using cmake directly
You can also use CMake directly and it should work just fine. If you want to use this option you probably know what you are doing
and need no help from me

# Dependencies
+ cmake 3.15+
+ perl  5       (only for build.pl script)
+ c++   20 
+ GTest         (no clue, I use newest)
+ 6502_Emulator (duh...)

# Usage & Workflow
//TODO: fill this later on


# MISC
this thing is still in beta. I will provide better documentation for it later. Maybe some casual examples

# Questions?
if so just ask me directly lol

