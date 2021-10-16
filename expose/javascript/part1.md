1) values added:  20
2) final result:  20
3) values added:  20
4) This line returns an error letting us know how the 'result' is not defined. The error was expected since 'let' was used to define the results variable. And, we know that variables defined with 'let' can only be accessed within the block they are defined in. 
5) This line returns an error specifically a TypeError related to assignment to constant variable. This error was expected since we are not allowed to reassign the value of a variable (like result here) which is defined using a const keyword. 
6) This line is not even executed. As Javascript executes code line-by-line, we know there was an error on line 9 so until that line gets executed, we won't be able to see any output from the line. On another note though, upon commenting line 9, I'm able to see some output from this line. The output is an error, which was expected since variables defined using 'const' are also block-spaced. 
