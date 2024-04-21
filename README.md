## UID: 605971914

## Pipe Up

Program that mimics shell pipe (|). 

## Building

To build my program, you just call make.
Command: make

## Running

After creating pipe, use ./pipe arg1 arg2 arg3 ... in order to run mimicked 
pipe command. That command is the equivalent of arg1 | arg2 | arg3 ...

Below is runnign the command

Command : ./pipe ls cat wc
Output: 8       8      74
Shell Command : ls | cat | wc
Output: 8       8      74
## Cleaning up

In order to clear all files, I use make clean.
Command: make clean 
