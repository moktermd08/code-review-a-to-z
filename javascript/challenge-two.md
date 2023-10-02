let arr = [1,2,3,4,5];
for (let i = 0; i < arr.length; i++) {
    console.log(arr[i]);
}


Use Modern Iteration: Use for...of loop for better readability.

```javascript
/**
 * Demonstrates how to iterate over an array using the for...of loop in JavaScript.
 * 
 * The for...of loop offers a more concise and readable way to iterate over 
 * array elements compared to the traditional for loop. Instead of using indices,
 * the for...of loop directly accesses each element, simplifying the code and
 * reducing the chances of off-by-one errors.
 */

// Initialize an array with sample numbers
let arr = [1, 2, 3, 4, 5];

// Use the for...of loop to iterate over each element in the array
for (let value of arr) {
    // Print the current element to the console
    console.log(value);
}
```
