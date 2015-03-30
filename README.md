# mathCompiler
a three pass math compiler

Eventually this is a simple calulator with basic functionality.
It displays a UI for composing a mathamatical expression and calculates the result f that expression via 3 steps:
1. tokenizes the expression into  { type, value } tokens
2. builds the abstract syntax tree out of those tokens
3. traverses the tree and calculates the result.

The insparation for this project came from codewars.com 'Three Pass Compiler' code kata.
