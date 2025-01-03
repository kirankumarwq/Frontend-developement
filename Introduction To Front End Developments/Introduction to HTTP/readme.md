# Introduction to HTTP

## Understanding HTTP and HTTPS

### What is HTTP?
- **Definition**: HTTP stands for Hypertext Transfer Protocol.
- Enables communication between a web browser (client) and a web server.
- Transfers web resources like HTML files, images, styles, and other content.
- Operates as a request-response protocol:
  1. Client (browser) sends an HTTP request.
  2. Server replies with an HTTP response.

### Components of an HTTP Request
1. **Method**: Defines the action the client wants to perform:
   - **GET**: Retrieve information from the server.
   - **POST**: Send data to the server.
   - **PUT**: Update an existing resource on the server.
   - **DELETE**: Remove a resource from the server.
2. **Path**: The location of the resource on the web server (e.g., `example.com/images/image.jpg`).
3. **Version**: Specifies the HTTP version used (e.g., HTTP/1.1 or HTTP/2).
4. **Headers**: Additional information about the request or client.
5. **Body (optional)**: Contains data sent with the request (e.g., form data in a POST request).

### Components of an HTTP Response
1. **Status Code**: Indicates the result of the request.
2. **Headers**: Provide additional metadata about the response.
3. **Body**: Contains the requested content (e.g., HTML document, image file).

### HTTP Status Codes
- **Informational (100-199)**:
  - Example: `100 Continue` – The client can proceed with the request.
- **Successful (200-299)**:
  - Example: `200 OK` – Request processed successfully.
- **Redirection (300-399)**:
  - Example: `301 Moved Permanently` – Resource has been moved to a new location.
  - Example: `302 Found` – Resource temporarily moved.
- **Client Errors (400-499)**:
  - Example: `400 Bad Request` – Syntax error in the request.
  - Example: `401 Unauthorized` – User must log in to proceed.
  - Example: `403 Forbidden` – Server refuses the request (insufficient permissions).
  - Example: `404 Not Found` – Requested resource does not exist.
- **Server Errors (500-599)**:
  - Example: `500 Internal Server Error` – Server failed to process the request.

### HTTPS: Securing Communication
- **Definition**: HTTPS (Hypertext Transfer Protocol Secure) is the secure version of HTTP.
- Uses encryption to protect data during transmission, ensuring:
  - Only the intended recipient can decode the data.
  - Sensitive information (e.g., credit card details) remains private.
- Indicated by a lock icon in the browser beside the URL.

### Key Points to Remember
- HTTP facilitates the exchange of data between browsers and servers.
- Requests consist of methods, paths, versions, headers, and sometimes a body.
- Responses return resources or status codes indicating success, errors, or other outcomes.
- HTTPS adds encryption to HTTP for secure communication.
