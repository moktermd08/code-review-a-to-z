function fetchData() {
    fetch("https://api.site.com/data")
    .then(response => response.json())
    .then(data => console.log(data));
}


Error Handling: Add a .catch() for potential errors from the fetch.


```javascript

/**
 * Fetches data from a specified API endpoint.
 * 
 * This function sends a request to a predefined API endpoint and then processes
 * the returned response. If the fetched data is in a valid JSON format, it prints
 * it to the console. If there's any error during the fetch operation or in processing
 * the response, an error message will be printed.
 */

function fetchData() {
    // Define the API endpoint URL
    const apiEndpoint = "https://api.site.com/data";
    
    // Initiate the fetch request to the specified endpoint
    fetch(apiEndpoint)
    .then(response => {
        // Check if the response is valid, otherwise reject the promise
        if (!response.ok) {
            throw new Error(`API request failed with status: ${response.status}`);
        }
        // Parse the response to JSON format
        return response.json();
    })
    .then(data => {
        // Print the processed data to the console
        console.log(data);
    })
    .catch(error => {
        // Handle any errors that occurred during the fetch or data processing
        console.error("Failed to fetch the data:", error.message);
    });
}
```

