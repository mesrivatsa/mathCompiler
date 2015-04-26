# MathCompiler
a three pass math compiler

The MathCompiler is a calculator that calcultes mathametical expressions. The cool thing about it is how the expressions are processed:
1. Tokenizing the expression into  { type, value } tokens
2. Building an abstract syntax tree out of those tokens
3. Traversing the tree and calculating the result. 

In this project I'm using HTML5, CSS3, pure JS with (some) jQuery for DOM manipulation. The app is mostly responsive, exclude mobile responsivness.

If your'e browsing through the code and want to know where all the magic happens, take a look at the 'TreeParser.parseExpression' method at parser.js that builds the AST out of the expression.

The insparation for this project came from codewars.com 'Three Pass Compiler' code kata.
