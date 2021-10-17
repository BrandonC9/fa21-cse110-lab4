1. Line 12 prints the last value i was assigned, which is 3. After the last iteration of the for-loop, i will be incremented one last time to 3. Since i is no longer less than prices.length, the loop breaks. 
2. Line 13 prints the last value discountedPrice was assigned, which is 150. 
3. Line 14 also prints the last value finalPrice was assigned, which is 150.
4. This function will return an array containing the values [50, 100, 150]. discounted starts off as an empty array, and has the new discounted prices pushed to the end of the array through each iteration.
5. This code will cause an error because line 12 is trying to print a variable that is no longer in-scope. i was declared using let, and that only allows i to be used in the for-loop block.
6. This code will cause an error because line 13 is trying to print a varialbe that is no longer in-scope. discountedPrice was declared using let in the for-loop block, and therfore cannot be used outside the for-loop.
7. Line 14 will print the last value finalPrice was assigned, which is 150. Since finalPrice is declared using let within the scope of the function, this code is valid.
8. This function will return an array containing the values [50, 100, 150]. Like finalPrice, discounted is declared using let within the scope of the function. Therefore, the code is valid.
9. This code will cause an error. i is declared using let within the scope of the for-loop, and therefore cannot be used outside that scope.
10. Line 12 will just print 3. length is assigned the lengthe of the input array, and is not reassigned anytime after it was first assigned.
11. This fucnction will return an array containing the values [50, 100, 150]. The function takes the input values and takes a 50 percent discount all the items, and pushes those new discounted values to the output array.
12. Data Types
    A. student.name
    B. student.Grad Year
    C. student.greeting()
    D. student.Favorite Teacher.name
    E. student.courseLoad[0];
13. Arithmetic Conversion
    A. '32' - '3' maps to its string representation and has 2 appended to it
    B. 1 - '3' maps to its number representaiton and has 2 subtracted from it
    C. 3 - null is coverted to 0, 3 + 0
    D. '3null' -  3 maps to its string represetation and has the string 'null' appended to it
    E. 4 - true maps to 1, 1 + 3
    F. 0 - both false and null map to 0
    G. '3undefined' - 3 maps to its string reprsentation and has 'undefined' appened to it
    H. NaN - undefined'd number representation is NaN, subtracting NaN from a number is NaN
14. Comparison
    A. true - '2' maps to its number representation, 2 is greater than 1
    B. false - both numbers are strings, '12' comes before '2' lexicographically
    C. true - 2 maps to its string representation, '2' is equal to '2'
    D. false - === does not convert the values to the same type, numerical 2 is not equal to string 2
    E. false - true maps to 1, 1 is not equal to 2
    F. true - the Boolean() function evaluates to true if the input parameter is not undefined or null. A Boolean object set to "false" is evaluated to true, and true is equal to true.
15. When using ==, the values are converted to the same type before comparison. === does not convert the values to the same type, and therefore the values must be completely identical for the expression to return true.
16. see part2-question16.js
17. The resulting array will be [2,4,6]. modifyArray iterates through each element in the input array. In each iteration, there is a callback to 'doSomething', which multiplies the current element by 2. This new value is the pushed back to newArr.
18. see part2.question18.js
19. Output will be:
    1
    4
    3
    2
