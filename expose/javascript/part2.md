1. The output is  **3** due to the for loop incrementing variable i 3  times, as the input array size is 3 . Additionally, `i` is var, and print statement in the function function scope, enabling it to be logged out on line 12. Then the print statement comes after the loop ends. 

2. The output is  **150** due to when variables with the same name being declared, the latest declaration overwrites the earlier ones when using the last element in the list which is 300. The print statement can access the variable because it has a function scope.
3. The output is  **150** since the variable will be reassigned to the final iterator for the last element which is 300. and the variable has function scope and it can access and update by the print statement.150 will be the output of line 14.
4. The output is **[ 50, 100, 150 ]**, The `discountPrices` function  takes in an array of prices and a discount percentage, and returns an array of discounted prices. The function uses a for loop to iterate through each item in the input `prices` array, calculates the discounted price for each item using the provided discount percentage, and adds it to a new array named `discounted`. The function then returns the `discounted` array containing the calculated discounted prices. When called with the input [100, 200, 300] and a discount percentage of 0.5, the function will return an array containing the discounted prices of [50, 100, 150] respectively for the original prices [100, 200, 300].
5.  The output is **ReferenceError: i is not defined**, the print statement is outside of the for-loop statment and `let` is declared in for-loop statement. and `let` is block scope. So it can't access the `i` variable.
6. The output is **ReferenceError: discountedPrice is not defined**, similar problem with Q5, `discountedPrice ` as declared `let` that is block scope and it outside of the for loop and can't access the `discountedPrice ` .
7. The output is **150**. `finalPrice` is declared in `discountPrices` function and after the final iteration of for loop discountPrices will be 150 .
8.  The output is **[ 50, 100, 150 ]**, The output of the given function with input parameters [100, 200, 300] and 0.5 is [50, 100, 150]. This is because the function applies a discount of 50% to each price in the input array, calculates the discounted price,  and then adds it to a new array named `discounted`. After all the elements in the input array have been processed, the function returns the `discounted` array containing the discounted prices. Therefore, the output of the function with the given input is an array containing the discounted prices of the original prices, which are [50, 100, 150].
9. The output is **ReferenceError: i is not defined**, `i` is `let` and `let` is block scope. and it can't print it in outside of for loop.
10. The output is `3`. the `price.length` is 3 as the array size is 3 where is 100,200,300.
11.  The output is **[ 50, 100, 150 ]**, The `discountPrices` function takes an array of prices and a discount rate as input, and returns an array of discounted prices. It does this by iterating over each element of the input array, calculating the discounted price for each item, and adding it to a new array. The final array is returned as output. The function uses a constant variable `length` to determine the length of the input array and a constant variable `discountedPrice` to hold the discounted price calculated for each element of the input array.
12. \
    a. student.name
    b. student['Grad Year']
    c. student.greeting()
    d. student['Favorite Teacher'].name
    e. student.courseLoad[0]
13. \
    A. **32**,the expression '3' + 2 results in the string '32' due to the concatenation of a string and a number
    B.  **1**, the expression '3' - 2 results in the numeric value 1 due to the subtraction of a coerced string from a number.
    C. **3**,the expression 3 + null results in the numeric value 3 because null is coerced to 0 in arithmetic operations.
    D.**3null**,the expression '3' + null evaluates to the string '3null' due to the concatenation of a string and a null value, which is coerced to the string 'null'.
    E.**4**, the expression true + 3 results in the numeric value 4 because true is coerced to the number 1 in arithmetic operations, and 1 + 3 equals 4.
    F.**0**,the expression false + null results in the numeric value 0 because both false and null are coerced to the number 0 in arithmetic operations, and 0 + 0 equals 0.
    G.**3undefined**,the expression '3' + undefined evaluates to the string "3undefined" because when a string is concatenated with an undefined value, the result is a string that includes the string value and the string representation of the undefined value.
    H.**NaN**, which stands for "Not a Number", because you can't perform arithmetic operations with undefined values in JavaScript.
14. 
    A.**true**, since '2' is coerced into a numeric value 2 and 2 is greater than 1.
    B.**false**,JavaScript compares strings lexicographically, which means that it compares the characters in the strings one by one, from left to right.
    C.**true**,The double equals (==) operator in JavaScript compares the values on either side of the operator and performs type coercion if necessary, so the expression `2` == 2 evaluates to true.
    D.**false**, As the strict equality operator `===` checks not only the value, but also the data type, and `2` is a string while 2 is a number.
    E. **false**,the `==` operator compares for value equality only after doing type conversions, and true is not equal to `2` after type conversion.
    F.**true**, The expression true === Boolean(2) is true in JavaScript. This is because the Boolean() function converts its argument to a boolean value. In this case, the argument is the number 2, which is converted to the boolean value true.
15. `==` is compares values for equality, but performs type coercion if necessary. `===` is compares values for equality, but without performing type coercion, making it a more strict comparison operator.
16. [code](./part2-question16.js)
17. The output is **[ 2, 4, 6 ]**,  `modifyArray` that takes an array and a callback function as arguments. The function creates an empty array called `newArr`, then loops through each element of the input array and applies the callback function to each element. The result of the callback function is then added to `newArr` using the `push()` method. Finally, the function returns the new array newArr containing the transformed values. the `doSomething` function takes a number and returns that number multiplied by 2. When the modifyArray function is called with the array [1, 2, 3] and the doSomething function as the callback, it loops through each element of the input array and applies the doSomething function to each element. The result is a new array [2, 4, 6], where each element in the original array has been multiplied by 2. This pattern of transforming data with a callback function is a common technique in JavaScript programming, and is often used in functional programming and event-driven programming paradigms.
18. [code](./part2-question18.js)
19. 
    1
    4
    3
    2

    

