# Reading 06:REST

## GROUP STUDY

1. Improved Collaboration Skills
2. Enhanced Problem-Solving Abilities
3. Greater Open-mindedness
Leadership Skills
4. Career Preparedness
5. Personal Growth

Learning to function and contribute effectively in a team setting is a valuable skill, and the insights from Google's quest to build the perfect team can provide actionable ways to improve teamwork and collaboration.

### Who is Roy Fielding?

Roy Fielding is a computer scientist, one of the principal authors of the HTTP specification and the originator of the Representational State Transfer (REST) architectural style. He has played a significant role in the development of the modern internet.

### Why don’t the techniques that we use in this class work well when we need to be able to talk to all of the machines in the world?

Many techniques used in computer science and programming are designed for specific, localized contexts. They often lack the universality and scalability required for global communication between all machines. The traditional techniques are not designed to communicate with any machine anywhere in the world, which is the fundamental requirement for the internet.

#### What is the HTTP protocol that Fielding and his friends created?

HTTP stands for HyperText Transfer Protocol. It's the underlying protocol used by the World Wide Web and defines how messages are formatted and transmitted, and what actions Web servers and browsers should take in response to various commands. It is a stateless protocol often run on TCP that allows for communication between clients and servers on the internet.

What does a GET do?
GET is a request method supported by HTTP used to request a representation of a specified resource. Requests using GET should only retrieve data and should have no other effect. Essentially, GET is used to retrieve data from the server.

#### What does a POST do?

POST is a request method supported by HTTP used to send data to a server to create a new resource. The data is included in the body of the request. This may result in the creation of a new resource or the updates of existing resources or both.

#### What does PUT do?

PUT is a request method supported by HTTP used to update a current resource with new data. The data is included in the body of the request. In contrast with POST, PUT is idempotent, meaning that the result of a single successful PUT request is the same as many identical PUT requests.

#### What does PATCH do?

PATCH is a request method supported by HTTP used for partial modifications to a resource. The request body contains the set of changes to be applied to the resource. It is used when you want to update one or more properties of the resource at a time, rather than replacing the entire resource.
