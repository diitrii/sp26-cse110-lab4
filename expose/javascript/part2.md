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
    F. 0 because 'false' counts as 0 so adding 'false' to 'null' keeps 0
    G. '3undefined' because undefined and 3 are counted as a string here
    H. NaN because subtracting undefined from 3 doesn't really count as a number
14.  
    A. true because integers and strings are kept as literals, so '2' is bigger than 1
    B. false, since these are strings, they aren't converted to numbers during conversion, so they just end up not equalling each other but the equality statements fall through
    C. true because with regular equality, string literals and integers are the same, so 2 is the same as '2'
    D. false, since this is "strict equality" so they do not equal each other
    E. false, since true = 1 and does not equal the number 2
    F. true, since strict equality checks without type conversion, and boolean(2) equals true, so the whole thing is true
15. difference between == and === is that == is normal equality which takes type conversion into account, and === is strict equality which does not take type conversion into account, so you can differentiate between 0 and 'false'
17. [2,4,6], what's happening is that the for loop runs three times for the amount of things in the array, and the callback is calling to "doSomething", which then multiplies each integer by 2
19. 1, 3, 2, 4