# Reading 08:NODE.APIs

*REST* stands for Representational State Transfer. It is an architectural style for networked hypermedia applications, often used in web services development.

*REST APIs* are designed around a resource. A resource can be essentially any coherent and meaningful concept that may be addressed.

An *identifier* of a resource is a URI (Uniform Resource Identifier) that uniquely identifies that resource. For example, https://api.example.com/users/123 could be an identifier for a user resource with the id 123.

### The most common HTTP verbs are:

1. GET: retrieve a specific resource (by id) or a collection of resources
2. POST: create a new resource
3. PUT: update a specific resource (by id)
4. DELETE: remove a specific resource by id

*URI*s* should be based on the nature of the resource and the operations that can be performed on it. URIs should be designed to help the API be self-describing, intuitive, and easy to use. They should be nouns (not verbs), and should follow a consistent, hierarchical structure.

### Here's an example of a good URI: https://api.example.com/users/123/posts. This URI is good because it's based on resources (users and posts), it's hierarchical (posts are a subset of a user), and it's intuitive (you can guess that it refers to posts made by a specific user).

A *'chatty'* web API is one that requires a client to make many individual requests to get all the needed data. This can be a bad thing because it can lead to performance issues. It's generally better to reduce the number of requests by designing the API in such a way that one request returns a larger amount of data.

### A successful GET request typically returns a status code of 200 (OK).

An unsuccessful **GET** request can return various status codes depending on the error, such as 404 (Not Found) if the resource doesn't exist, or 400 (Bad Request) if the request was malformed.

A successful *POST* request that results in the creation of a new resource typically returns a status code of 201 (Created).

A successful *DELETE* request typically returns a status code of 200 (OK) if the response includes a message body, or 204 (No Content) if the response does not include a message body.

## Things I want to know more about

Everything we learned about the first week