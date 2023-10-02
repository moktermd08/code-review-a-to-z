const obj = { name: "John", age: 30, city: "New York" };
const myJSON = JSON.stringify(obj);

```javascript
/**
 * Demonstrates how to convert a JavaScript object to a JSON string.
 * 
 * In this example, we have a user object with properties like name, age, and city.
 * We then convert this object into a JSON string for purposes such as sending 
 * the data to a server or saving it in a structured format.
 */

// Define a user object with some properties
const obj = {
    name: "John",
    age: 30,
    city: "New York"
};

// Convert the user object to a JSON string
const userJSON = JSON.stringify(obj);

// (Optional) Log the JSON string to the console for verification
console.log(userJSON);  // Expected output: '{"name":"John","age":30,"city":"New York"}'
```
