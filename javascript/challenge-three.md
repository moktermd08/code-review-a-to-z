```javascript
function login(user, pass) {
    if (user == "admin" && pass == "12345") {
        return true;
    }
    return false;
}
```

Review:

Security: Hardcoding credentials is insecure. Use environment variables or authentication services.


```javascript
/**
 * A simple login function to demonstrate the concept.
 * 
 * IMPORTANT NOTE:
 * This function contains hardcoded credentials, which is a major security concern.
 * For real-world applications, always use environment variables or trusted authentication 
 * services to handle user credentials.
 * 
 * @param {string} user - The username provided for login.
 * @param {string} pass - The password provided for login.
 * @returns {boolean} - Returns true if the credentials match, false otherwise.
 */

function login(user, pass) {
    // WARNING: Hardcoded credentials. This is not a secure practice.
    const hardcodedUsername = "admin";
    const hardcodedPassword = "12345";
    
    // Check if the provided credentials match the hardcoded ones
    if (user === hardcodedUsername && pass === hardcodedPassword) {
        // Return true if credentials match
        return true;
    }
    
    // Return false if credentials do not match
    return false;
}

```
