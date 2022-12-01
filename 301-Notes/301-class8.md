# 301 Class 8 Reading Notes - APIs

[API Design Best Practices](https://docs.microsoft.com/en-us/azure/architecture/best-practices/api-design)

1. What does REST stand for?
In 2000, Roy Fielding proposed Representational State Transfer (REST) as an architectural approach to designing web services. 
REST is an architectural style for building distributed systems based on hypermedia. 
REST is independent of any underlying protocol and is not necessarily tied to HTTP. 
However, most common REST API implementations use HTTP as the application protocol, and this guide focuses on designing REST APIs for HTTP.

2. REST APIs are designed around (resources).

3. What is an identifier of a resource? Give an example.
A resource has an identifier, which is a URI that uniquely identifies that resource. For example, the URI for a particular customer order might be:
````markdown
    HTTP
    https://adventure-works.com/orders/1
````
4. What are the most common HTTP verbs?
GET, POST, PUT, PATCH, and DELETE.

5. What should the URIs be based on?
When possible, resource URIs should be based on nouns (the resource) and not verbs (the operations on the resource).

6. Give an example of a good URI.
https://adventure-works.com/orders // Good

https://adventure-works.com/create-order // Avoid

10. What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?
"chatty" web APIs expose a large number of small resources. Such an API may require a client application to send multiple 
requests to find all of the data that it requires.

11. What status code does a successful GET request return?
A successful GET method typically returns HTTP status code 200 (OK). 

12. What status code does an unsuccessful GET request return?
If the resource cannot be found, the method should return 404 (Not Found).
If the request was fulfilled but there is no response body included in the HTTP response, 
then it should return HTTP status code 204 (No Content); for example, a search operation yielding no matches 
might be implemented with this behavior.

13. What status code does a successful POST request return?
If a POST method creates a new resource, it returns HTTP status code 201 (Created).

14. What status code does a successful DELETE request return?
If the delete operation is successful, the web server should respond with HTTP status code 204 (No Content), 
indicating that the process has been successfully handled, but that the response body contains no further information. 
If the resource doesn't exist, the web server can return HTTP 404 (Not Found).

## Bookmark and Review
[RegExr](https://regexr.com/)
[Regex Tutorial](https://medium.com/factory-mind/regex-tutorial-a-simple-cheatsheet-by-examples-649dc1c3f285)
[Regex 101](https://medium.com/factory-mind/regex-tutorial-a-simple-cheatsheet-by-examples-649dc1c3f285)

## things I wanna know more about
A visual of how this all comes into play
