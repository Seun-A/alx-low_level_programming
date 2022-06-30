# C: Hello, World

## Table of Content: 
<br />

| File | File Description | 
--- | ---
<br/><span style="font-size: 1.7rem">**Mandatory**</span>
[0-preprocessor](./0-preprocessor) | Script that runs a C file through the preprocessor and save the result into another file <ul><li>The C file name will be saved in the variable `$CFILE`</li><li>The output should be saved in the file `c`</li></ul>
[1-compiler](./1-compiler) | Script that compiles a C file but does not link <ul><li>The C file name will be saved in the variable `$CFILE`</li><li>The output file should be named the same as the C file, but with the extension `.o` instead of `.c`. <ul><li>Example: if the C file is `main.c`, the output file should be `main.o`</li></ul></li></ul>
[2-assembler](./2-assembler) | Script that generates the assembly code of a C code and save it in an output file <ul><li>The C file name will be saved in the variable `$CFILE`</li><li>The output file should be named the same as the C file, but with the extension `.s` instead of `.c`. <ul><li>Example: If the C file is `main.c`, the output file should be `main.s`</li></ul></li></ul>
[3-name](./3-name) | Write a script that compiles a C file and creates an executable named `cisfun` <ul><li>The C file name will be saved in the variable `$CFILE`</li></ul>
[4-puts.c](./4-puts.c) | C program that prints exactly `"Programming is like building a multilingual puzzle`, followed by a new line <ul><li>Use the function `puts`</li><li>You are not allowed to use `printf`</li><li>Your program should end with the value `0`</li></ul>
[5-printf.c](./5-printf.c) | C program that prints exactly `with proper grammar, but the outcome is a piece of art,`, followed by a new line <ul><li>Use the function `printf`</li><li>You are not allowed to use the function `puts`</li><li>Your program should return `0`</li><li>Your program should compile without warning when using the `-Wall` `gcc` option</li></ul>
[6-size.c](./6-size.c) | C program that prints the size of various types on the computer it is compiled and run on <ul><li>You should produce the exact same output as in the example</li><li>Warnings are allowed</li><li>Your program should return `0`</li><li>You might have to install the package `libc6-dev-i386` on your Linux to test the `-m32` `gcc` option</li></ul>

# 
<br>

## **Author:** [Seun Ajayi](https://github.com/Seun-A)