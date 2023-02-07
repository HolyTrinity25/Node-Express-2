### Conceptual Exercise

Answer the following questions below:

- What is a JWT?
JWT are an open standard and implemented across technology stacks, making it simple to share tokens across different services.

- What is the signature portion of the JWT?  What does it do?
version of header & payload signed with secret key. Uses algorithm specified in header.

- If a JWT is intercepted, can the attacker see what's inside the payload?
- data to be stored in token and often, this will store things like the user ID. This is encoded not encrypted - don't put secret info here. 

- How can you implement authentication with a JWT?  Describe how it works at a high level.
-Make request with username/password to AJAX login route. and serves authenticates and returns token in JSON. Server gets token from request and validates token.

- Compare and contrast unit, integration and end-to-end tests.
-A unit test is a test of a particular function and how well it works on it's own. Integration tests test the interconnectivity of multiple functions, often testing a particular app feature and all it's component parts at once. End-to-end test are more comprehensive and will test the entire application in order to evaluate the entire user experience across the app.

- What is a mock? What are some things you would mock?
-primarily used in unit testing. An object  under test may have dependencies on other complex objects. It can be faster and do not have to wait for an API response and deal with rate limits. You can mock AJAX requests, Reading and Writing to files and impure functions like Math.random

- What is continuous integration?
- the practice of merging in small code changes frequently, rather than merging in a large at the end of a development cycle.

- What is an environment variable and what are they used for?
Environment variables are used to store app secrets and configuration data, which are retrieved by your running app when needed.
- What is TDD? What are some benefits and drawbacks?
-TDD (Test Driven Development) is a practice in development in which the programmer will start by writing tests, then begin building out the application to satisfy those tests. This can be useful in assuring you know exactly what you want a program to do or not do and can keep you from making mistakes that may "break" other parts of an application. It tends to be a bit slower and can get a little excessive when there are more lines of test code than actual production code.

- What is the value of using JSONSchema for validation?
-Testing and validating JSON APIs is an important aspect of running a quality web service, but managing checks for large and diverse response bodies can be difficult. Using JSON Schema to construct a model of your API response makes it easier to validate your API is returning the data is should.

- What are some ways to decide which code to test?
Do not get too attached to coverage percentages

- What does `RETURNING` do in SQL? When would you use it?
the RETURNING clause allows you to retrieve values of columns (and expressions based on columns) that were modified by an insert, delete or update.

- What are some differences between Web Sockets and HTTP?
HTTP is a pretty wordy and heavy protocol and is stateless. Websockets are tiny and stateful and they stay connected.

- Did you prefer using Flask over Express? Why or why not (there is no right
  answer here --- we want to see how you think about technology)?

 "Node.js" and "Javascript" are the key factors why I  consider ExpressJS
