```javascript
setTimeout(function() {
    console.log("Done!");
}, 3000);
```
Use Arrow Functions: Makes the code cleaner.


```javascript
/**
 * Demonstrates the use of setTimeout with arrow functions.
 * 
 * setTimeout is a JavaScript function that allows you to delay the execution 
 * of a specific function by a specified number of milliseconds. Here, we delay
 * the logging of the message "Done!" by 3 seconds. Using an arrow function as 
 * the callback makes the code more modern and concise.
 */

// Use setTimeout to delay the execution of the provided function by 3000 milliseconds (3 seconds)
// The arrow function provides a cleaner and more concise syntax for the callback
setTimeout(() => {
    // Log the message to the console after the delay
    console.log("Done!");
}, 3000);

```
