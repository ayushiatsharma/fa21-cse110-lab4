#1) It prints out 3. Since variables declared with var (like i) are function-scoped, it makes sense that there wasn't any error and 3 was printed out after going through the for loop before. 

#2) It prints out 150. Since variables declared with var (like discountedPrice) are function-scoped, it makes sense that there wasn't any error and 150 was printed out after going through the for loop before. 

#3) It prints out 150. Since variables declared with var (like finalPrice) are function-scoped, it makes sense that there wasn't any error and 150 was printed out after going through the for loop before. 

#4) This function returns discounted array, which holds the following values: [ 50, 100, 150 ]. These values are a result of the for loop before the return statement in the functioin. The discounted array values won't be printed as an output until we console.log() the result after calling the function. Also, since discounted array was declared with a var keyword, we know it would be accessible throughout the function.

#5) There was an error about how the variable i is not defined. The error is the result of using let to define i variable. These kind of variables are not accessible outside a specific block where they are defined at (which in this case is the for loop in the function). 

#6) We get a similar error for line 13 too. Since variables defined with let are block-spaced, we won't be able to see the value of discountedPrice is outside the block it's defined in (which in this case is the for loop in the function).

#7) It prints out 150 because this line is within the block where this variable finalPrice is defined in.

#8) It would return [ 50, 100, 150 ] but not print out anything to the screen since the output is not console-logged. This is returned because even though this array is defined using let, but this line is still within the block where the variable is defined. 

#9) There was an error about how the variable i is not defined. The error is the result of using let to define i variable. These kind of variables are not accessible outside a specific block where they are defined at (which in this case is the for loop in the function). 

#10) It prints out 3 since the length of the input array is 3.

#11) It would return [ 50, 100, 150 ] but not print out anything to the screen since the output is not console-logged. This is returned because this variable is defined using const and it's not reassigned within it's block.

#12) A) student.name

#12) B) student["Grad Year"]

#12) C) student.greeting

#12) D) student['Favorite Teacher']['name']

#12) E) student['courseLoad'][0]

#13) A) 32. Here the int 2 is considered as string and hence concatenated with the string 3 in the front giving us 32 as the final output.

#13) B) 1. Here '3' becomes 3 (of type int) and then 2 is subtracted returning 1. 

#13) C) 3. Here null is considered as 0 and hence have no effect. 

#13) D) 3null. Here null becomes 'null' (of type string) hence giving 3null as output.

#13) E) 4. Here true becomes 1 and is added to 3 returning 4.

#13) F) 0. Here false is 0 and null is 0, which's why adding them results in 0. 

#13) G) 3undefined. Here undefined is considered of type string and hence put together with 3 like this.

#13) H) NaN. Since one of the variables for subtraction is undefined, we get this as output.

#14) A) true. Since we are comparing a string with a number, the string would be converted to a number. This is why 2>1 results in true.  

#14) B) false. Since here two strings are comapred, we'll see the element at the first index of both the strings. And, since 2>1, we get false as the output. 

#14) C) true. The == operator only compares the value of the two variables hence result is true. 

#14) D) false. The === operator also makes sure whether the type of the two variables is same or not. Since the comparison is between a string and an integer, we get false as the output. 

#14) E) false. This results in false becuase true would be 1 as an integer not 2. 

#14) F) true. Here Boolean(2) returns true as this Boolean function returns true for any non-zero, non-null, etc. kind of inputs. This leaves us with comparing true and true which in results give us true too. 

#15) The == operator compares only values of two things that are being compared whereas the === compares not only the value but also the type of the two things that are compared.  

#16) In part2-question16.js file 

#17) The result would be [ 2, 4, 6 ]. The function call from line 13 would take us to the start of the function defined at line  1. We would go through this modifyArray function. A new const array would be created at line 2 followed up a for loop where the doSomething function is called to push new values to the newArr array. The doSomething() function would returnn a value such as 2 for when the for loop covers input of 1  followed by 2 (pushing 4 to newArr for this) and 3 (pushing 6 to newArr for this) from the input array. Finally the newArr is returned after it's doen updating from the calls to doSomething within the for loop. 

#18) In part2-question18.js file

#19) It prints out the following in it's own line: 
1
4
3
2
