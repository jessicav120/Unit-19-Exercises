# Unit-19-Exercises
Practice files for understanding how the web works, AJAX, and BigO notation

### How Web Works Exercise Answers
1. What is HTTP?
    - HTTP stands for Hypertext Transfer Protocol, and is a set of rules for browser-server communication. It defines standards for data included in browser requests and server responses.

2. What is a URL?
    - URL stands for Universal Resource Locator and is a string that includes the protocol, hostname, port, resource, and any queries. It is included in the request. 

3. What is DNS?
    - DNS stands for Domain Name System and is the human-readable “nickname” for an IP address. 

4. What is a query string?
    - A query string is a string containing the arguments submitted to the server, like user data or a search query. It is found at the end of the URL. 

5. What are two HTTP verbs and how are they different?
    - There are GET and POST. A GET request doesn’t change any server data, and simply returns the requested data. A POST request does change server data, like when entering user data or making a new instagram post. 

6. What is an HTTP request?
    - An HTTP request is sent by the browser to the server, asking for certain data or pages, or to make some changes following the HTTP protocol. It contains the exact URL of a webpage, and typically multiple requests are made at once.

7. What is an HTTP response?
    - An HTTP response is sent by the server to the browser, containing all the HTML/code requested by the server.
  
8. What is an HTTP header? Give a couple examples of request and response headers you have seen.
    - Headers are additional information to include in requests and responses. One example would be the Accept-Language header, which specifies which language the webpage content should be. Another would be Date, which returns the date and time a message was sent.

9. What are the processes that happen when you type “http://somesite.com/some/page.html” into a browser?
    - Translate somesite.com into an IP address
    - Connect to the IP address using HTTP protocol on port 80
    - Ask the server for /some/page.html
