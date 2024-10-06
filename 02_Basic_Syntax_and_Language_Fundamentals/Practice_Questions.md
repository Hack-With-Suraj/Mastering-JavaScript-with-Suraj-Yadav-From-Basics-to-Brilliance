## 1. What is the difference between let and const keywords in JavaScript?
let: Assigning any variable to a value you might change later.
const: This is used to define a variable whose value will remain the same throughout the life class.

## 2. How do you determine the data type of a variable in JavaScript?
Use the typeof operator:
```
let number = 10;
console.log(typeof number); // Output: "number"
```
## 3. Explain the concept of reference types in JavaScript. How do they differ from primitive types?
Reference types: Objects and Arrays in JavaScript Variables only contain these references to the objects, but not the value of what they point to.
Primitive types are just simple values like numbers, strings, booleans, null and undefined. Values are placed in variables directly.

## 4. What is the purpose of the ternary operator in JavaScript? Provide an example.
The ternary operator is a concise way to write conditional expressions.
```
let isAdult = age >= 18 ? "Yes" : "No";
```
## 5. Explain the difference between the == and === operators.
==: Compares values, performing type coercion if necessary.
===: Compares both values and types strictly.
## 6. What are bitwise operators used for in JavaScript?
Bitwise operators are used for low-level operations on individual bits of numbers.

## 7. When would you use an if-else statement versus a switch statement?
if-else: Use for simple conditions or when you need to check multiple conditions.switch: Use for comparing a single expression against multiple values.                      
## 8. What is the importance of the break statement in a switch case?
break prevents the execution of subsequent cases if a match is found.

## 9. What is the difference between a for loop and a while loop?
for: Used when you know the number of iterations beforehand.
while: Used when the number of iterations is unknown.

## 10. When would you use a do-while loop instead of a while loop?
 you can Use do-while loop if you want to execute the code at least once, even if the condition is initially false.