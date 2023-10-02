***Original Method***
```javascript
let numbers = [1, 2, 3];
``

let doubled = numbers.map(function(n) { return n * 2 });


Use Arrow Functions: This provides a concise way to write the function.

***Revised Method***

```javascript
/**
 * Demonstrates how to use arrow functions to make code more concise.
 * 
 * In this example, we take an array of numbers and return a new array where
 * each number is doubled. The transformation is done using the .map() method
 * combined with an arrow function for brevity and clarity.
 */

// Initialize an array with sample numbers
let numbers = [1, 2, 3];

// Use the .map() method to create a new array with each number doubled
// The arrow function provides a concise way to define the transformation logic
let doubled = numbers.map(n => n * 2);

// (Optional) Print the result to console
console.log(doubled);  // Expected output: [2, 4, 6]

```
