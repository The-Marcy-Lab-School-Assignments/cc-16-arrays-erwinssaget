# Code Challenge: Control Flow

## Instructions

1. Clone down this assignment to your `code-challenges' directory in AWS Cloud9.  
2. Code your solution using JavaScript in `index.js`. 
3. **Be sure to run and test your code throughly!**
4. By the end of Code Challenge, **commit and push your changes up to Github**.
5. Using the browser, verify that your solution is in your remote repo on Github.

## Code Problems

1. Declare a function named `replaceWithYerr` that accepts three arguments: an Array, a start index, and the number of elements to replace with the string 'yerr'. The function should return a **new** Array, with the same elements as the original Array, except elements at the starting index, are replaced with the string 'yerr'. The number of elements replaced is determined by the third argument. 

**Note**: The second and third arguments are *optional*. If the third argument is missing, the function should return replace all elements from the starting index to the end of the array. If only an array argument is passed, it should return a copy of the array argument, with all elements replaced.
```
const months = ['Jan', 'February', 'March', 'April', 'May', 'June'];

replaceWithYerr(months, 1, 3) //['Jan', 'yerr', 'yerr, 'yerr', 'May', 'June']
replaceWithYerr(months, 1) //['Jan', 'yerr', 'yerr, 'yerr', 'yerr', 'yerr']
replaceWithYerr(months) //['yerr', 'yerr', 'yerr, 'yerr', 'yerr', 'yerr']
```
