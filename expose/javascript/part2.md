# Part 2

1.  Prints `3` since `var` defines `i` within the function scope, and it is printed within the function.
2.  Prints `150` since `var` defines `discountedPrice` within the function scope, and it is printed within the function.
3.  Prints `150` since `var` defines `finalPrice` within the function scope, and it is printed within the function.
4.  Returns the following array: `[ 50, 100, 150 ]` because we called the function with the arguments [100, 200, 300] and 0.5. So, for each item in [100, 200, 300], we multiply its price by (1-0.5), push it to discounted, then return discounted. In other words, we halve each price. Since there are no errors, the function works as intended.
5.  Throws the error: `ReferenceError: i is not defined`. This is because when we say `let i = 0;`, we are only defining i for the scope of the for loop. Thus, when we try to print it outside the for loop, we get an error.
6.  Throws the error: `ReferenceError: discountedPrice is not defined`. This is because when we define discountedPrice within the for loop using `let`, so it is only defined within the scope of the for loop. Thus, when we try to print it outside the for loop, we get an error.
7.  prints `150` since `finalPrice` is defined within the same scope where it is printed.
8.  Returns the following array: `[ 50, 100, 150 ]` because we called the function with the arguments [100, 200, 300] and 0.5. So, for each item in [100, 200, 300], we multiply its price by (1-0.5), push it to discounted, then return discounted. In other words, we halve each price. Since there are no errors, the function works as intended.
9.  Throws the error: `ReferenceError: i is not defined`. This is because when we say `let i = 0;`, we are only defining i for the scope of the for loop. Thus, when we try to print it outside the for loop, we get an error.
10. Prints `3`. This is because length is both defined and printed in the same scope, so there is no issue.
11. Returns the following array: `[ 50, 100, 150 ]` because we called the function with the arguments [100, 200, 300] and 0.5. So, for each item in [100, 200, 300], we multiply its price by (1-0.5), push it to discounted, then return discounted. In other words, we halve each price. Since there are no errors, the function works as intended.
12. Notation:
    - A. `student.name;`
    - B. `student["Grad Year"];`
    - C. `student.greeting();`
    - D. `student["Favorite Teacher"].name;`
    - E. `student.courseLoad[0]`
13. Notation:
    - A. `'32'`
    - B. `1`
    - C. `3`
    - D. `'3null'`
    - E. `4`
    - F. `0`
    - G. `3undefined`
    - H. `NaN`
14. Results:
    - A. `true`
    - B. `false`
    - C. `true`
    - D. `false`
    - E. `false`
    - F. `true`
15. `==` does type conversion before comparing `===` compares data types and values
16. Answered in JS
17. The result of calling the function with those parameters is the following array: `[ 2, 4, 6 ]`. This is because `modifyArray` calls `doSomething` on each element in the array, which doubles the input.
18. Answered in JS
19. It would print the following:
    ```
    1
    4
    3
    2
    ```
