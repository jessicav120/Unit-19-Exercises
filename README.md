# Unit-19-Exercises
Practice files for understanding how the web works, AJAX, and BigO notation

## How Web Works Exercise Answers
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
  
## Big O Notation Exercise Answers
### Part 1: Simplify the following Big O Expressions 
1. O(n + 10) - O(n)
2. O(100 * n) - O(n)
3. O(25) - O(1)
4. O(n^2 + n^3) - O(n^3)
5. O(n + n + n + n) - O(n)
6. O(1000 * log(n) + n) - O(n)
7. O(1000 * n * log(n) + n) - O(nlogn)
8. O(2^n + n^2) - O(2^n)
9. O(5 + 3 + 1)	- O(1)
10. O(n + n^(1/2) + n^2 + n * log(n)^10) - O(n^2)
 
 ### Part 2: Calculate Time Complexity
1. O(n)
2. O(n)
3. O(1)
4. O(n)
5. O(n^2)
6. O(n)

### Part 3: Short Answer
1. True or false: n^2 + n is O(n^2). **True**
2. True or false: n^2 * n is O(n^3). **True**
3. True or false: n^2 + n is O(n). **False (O(n^2))**
4. What’s the time complexity of the .indexOf array method? **O(n)**
5. What’s the time complexity of the .includes array method? **O(n)**
6. What’s the time complexity of the .forEach array method? **O(n)**
7. What’s the time complexity of the .sort array method? **O(nlogn)**
8. What’s the time complexity of the .unshift array method? **O(n)**
9. What’s the time complexity of the .push array method? **O(1)**
10. What’s the time complexity of the .splice array method? **O(n)**
11. What’s the time complexity of the .pop array method? **O(1)**
12. What’s the time complexity of the Object.keys() function? **O(n)**


 
