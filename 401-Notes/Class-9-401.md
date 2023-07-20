# Class 9 Reading Notes

These readings cover the basics of the HTTP request cycle and how to make HTTP requests in Java.

## High-level HTTP

- What are the five steps in the HTTP Request Lifecycle?

> Local Processing, Resolving the IP, Establish a TCP Connection, Send an HTTP Request, Tearing Down and Cleaning Up.

- What are the two things the client needs before it can make an HTTP Request?

> Resolve the IP address and open a TCP connection.

- Explain the four way handshake and what it does.

> The four way handshake is a process used by TCP to establish a reliable connection between a client and a server.  1 - The client sends a SYN packet to the server. 2 - Server responds with a SYN-ACK packet. 3 - Client sends an ACK packet. 4 - Connection established and data transmission begins.


## Java HTTP Request Example

- True or False: When making an HTTP request, you MUST follow any redirect returned by the request. Back up your answer.

> False, we can enable or disable automatically following redirects for any specific connections. For instance: `HttpUrlConnection.setFollowRedirects(false);`

- Which built-in Java class can be used to perform an HTTP request?

> HttpUrlConnection class allows us to perform basic HTTP requests.

- What HTTP status codes represent a successful response? A redirect? A client error?

> Sucessful: 200 - OK, 201 Created.  
> Redirect: 301 - Moved Permanently, 302 Found (or 307 Temporary Redirect)  
> Client Error: 400 - Bad Request, 404 - Not Found
