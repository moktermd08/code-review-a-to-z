```javascript
const user = { name: "John", isAdmin: false };
if (user.isAdmin == true) {
    console.log("Admin");
}
```

```javascript

/**
 * Demonstrates the use of strict equality in JavaScript.
 * 
 * It's a best practice to use strict equality (===) over loose equality (==) 
 * to ensure both value and type match during comparisons. This helps in avoiding
 * potential pitfalls due to JavaScript's type coercion.
 * 
 * In this example, we're checking if a user object has a property 'isAdmin' set to true,
 * and if so, we log a message to the console.
 */

// Define a sample user object with properties 'name' and 'isAdmin'
const user = {
    name: "John",
    isAdmin: false
};

// Use strict equality to check if 'isAdmin' property is set to true
if (user.isAdmin === true) {
    // Log a message to the console if the condition is met
    console.log("Admin");
}


```
