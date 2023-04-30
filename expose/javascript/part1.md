1. values added: 20
2. final result: 20
3. values added: 20
4. It occur **ReferenceError: result is not defined**. The reason have this error as `result` is declared using the `let` and `let` have block scope. it means that `result` can not be redeclared, therefore its scope is limited to that block.When the line 13 is executed outside of the if block, the JavaScript interpreter cannot find the `result` variable in the current scope and throws an error.
5. It occur **TypeError: Assignment to constant variable**. The reason have this error as `result` is declared by `const`. `const` cannot be redeclared and reassigned. Also have Block Scope. And line 9 try to reassign it so it occur the error.
6. **TypeError: Assignment to constant variable**, and same reason with question 5.line 13 try to reassign it so it occur the error. Also, `const` is defined within the if statement and const is block scope .It cannot be access outside of the if statement.
