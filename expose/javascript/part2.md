1. the console will print the length of "prices", because that's the length that variable "i" ends up at after the for loop terminates.
2. the console will print the variable "discountedPrice" after the for loop, which will print the last thing that "discountedPrice" was set to
3. again, "finalPrice" is also a "var" declaration, meaning it is only within function scope, so the console will print the last thing that variable "finalPrice" was set to.
4. The function will return the last thing the array "discounted" was set to, since again, "discounted" is set as a "var".
5. "i" will print an error, since the print statement is outside the for loop, and the variable is set to "let".
6. "discountedPrice" will print an error, since it is within the "if" statement, and the print statement is outside the "if" statement
7. "finalPrice" will print whatever the last iteration of the for loop is.
8. "discounted" will return an array containing all of the values of "finalPrice" throughout the for loop.
9. An error will print because "i" is being printed outside of scope
10. The length of "prices" will be printed because the variable is constant.
11. The function will return an empty array because the "discounted" variable is constant and cannot be altered.
12.  
    A. student.name
    B. student["Grad Year"]
    C. student.greeting()
    D. student["Favorite Teacher"].name
    E. student.courseLoad[0]
13.  
    A. '32' since integers map to their exact string representation
    B. 1 since integers map to exact string representation
    C. 3, since null means nothing, so adding null to 3 just remains 3
    D. '3null' since it's a string, so 'null' is a string and it just treats the whole thing as a string
    E. 4 because 'true' is counted as a 1, so 3 + 1 = 4
    F. 0 because 