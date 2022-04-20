# CLI_Calculator

### Abstract

A command line calculator which supports mathematical expressions with scientific functions is very useful for most developers.
The command line is a text interface for your computer. It's a program that takes in commands, which it passes on to the computer's operating system to run. It is a convenient interface to use for most coding enthusiasts.
Keeping that in mind, we decided that a calculator which can be run from the common line itself, without opening an external application would be a convenient tool.
Our command line calculator is capable of parsing a human-readable mathematical expression with units, returning the value if it can be evaluated and informing the user about the position of an error if not. 
We utilized the concepts of Compiler Design by building our CLI calculator using a Lexer and Recursive Descent Parsing.

### Concepts Used

- Recursive Descent Parsing 
- Lexical Analysis

### Usage Guidelines

- Open your terminal and clone the repository

        git clone https://github.com/sashrika15/CLI_Calculator.git
        
- Change to model directory

        cd CLI_Calculator

- Compile the code
  - Unix
  
        gcc -o calc -lm cli_calc.c

  - Windows:
  
        cl /out:calc.exe cli_calc.c
        
 - Run the executable calculator on command prompt


### References
We would like to thank [Steve Hanov's Blog](http://stevehanov.ca/blog/?id=26) for the reference.
