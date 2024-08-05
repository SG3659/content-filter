# Fetch API
## Advantages 
1. Built-in: Fetch is a native JavaScript API, meaning it doesn't require any additional libraries or dependencies.
2. Promise-based: Fetch returns a promise that resolves to the response of the request, making it easy to work with asynchronous code using .then() and async/await.
3. Streaming: Fetch supports streaming of responses, which can be useful for handling large files.

## Disadvantages   
1. Verbose: Fetch can require more boilerplate code, especially for error handling and parsing JSON responses.
2. Limited Features: Fetch lacks some of the advanced features that Axios provides, such as automatic transformation of JSON data, request cancellation, and timeout handling.
3. No Built-in Timeout: Fetch doesn't have a built-in way to handle request timeouts. You need to implement it manually using AbortController.


