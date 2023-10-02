function fetchData() {
    fetch("https://api.site.com/data")
    .then(response => response.json())
    .then(data => console.log(data));
}


Error Handling: Add a .catch() for potential errors from the fetch.
