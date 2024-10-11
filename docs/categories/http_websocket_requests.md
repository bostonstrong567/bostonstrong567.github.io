# HTTP and WebSocket Requests

This section covers all functions related to HTTP requests and WebSocket management.

## HTTP and WebSocket Functions

### [request](../examples/request_example.md)
Makes a HTTP request.

**Description:**
`request` is used to make HTTP requests, allowing for interaction with web APIs through standard RESTful methods such as GET, POST, PUT, and DELETE.

**Arguments:**
- `options` *(table)*: A table containing details about the request (e.g., URL, method, headers).

**Returns:**
- *(table)*: A response table that contains information such as the status code and body of the response.

---

### [http_request](../examples/http_request_example.md)
Performs an HTTP request.

**Description:**
`http_request` is another function used to execute HTTP requests, allowing for a variety of HTTP methods including custom headers and bodies.

**Arguments:**
- `options` *(table)*: A table specifying request parameters like URL, method, headers, and body.

**Returns:**
- *(table)*: The response from the server, including status and data.

---

### [HttpGet](../examples/HttpGet_example.md)
Performs a GET request.

**Description:**
`HttpGet` simplifies making HTTP GET requests to retrieve information from a given URL.

**Arguments:**
- `url` *(string)*: The URL to send the GET request to.

**Returns:**
- *(string)*: The response data from the server.

---

### [HttpGetAsync](../examples/HttpGetAsync_example.md)
Performs an asynchronous GET request.

**Description:**
`HttpGetAsync` allows for making a non-blocking GET request, useful when the script needs to continue running without waiting for the response.

**Arguments:**
- `url` *(string)*: The URL to send the GET request to.

**Returns:**
- *(function)*: A callback function that processes the response when available.

---

### [WebSocket](../examples/WebSocket_example.md)
Creates a new WebSocket connection.

**Description:**
`WebSocket` allows for the creation of a WebSocket connection, facilitating real-time, full-duplex communication with a server.

**Arguments:**
- `url` *(string)*: The URL of the WebSocket server to connect to.

**Returns:**
- *(object)*: A WebSocket object that can send and receive messages.

**Methods:**
- `send` *(string)*: Sends a message through the WebSocket.
- `close` *(void)*: Closes the WebSocket connection.