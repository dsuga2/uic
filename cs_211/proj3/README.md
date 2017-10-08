# CS 211 Project 3

Due date: Monday, Oct. 10th

### Usage
A makefile is provided for easier compilation. Enter `make` or `make proj3` to build the project. Enter `make run` to run the executable. If you want to build and run, just enter `make all`. If you want to build and run in debug mode, enter `make debug`.
Recompilation should work just fine with `make`, since the source files are set as dependencies for the build process.

For manual compilation, type `gcc -g -o proj3 maze.c main.c`. Then run the executable using `./proj3`.

To clean up, enter `make clean`.