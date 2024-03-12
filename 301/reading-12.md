# Readings: CRUD

## [Status Codes Based On REST Methods](https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/)) 
1. **In your own words, describe what each group of status code represents:**
* **100’s=** These status codes indicate informational responses and are typically used to acknowledge that the request has been received and understood.
* **200’s=** These status codes indicate successful responses, informing the client that their request was successfully received, understood, and processed.
* **300’s=** These status codes indicate redirection responses, informing the client that further action needs to be taken to complete the request, such as redirecting to a different URL.
* **400’s=** These status codes indicate client error responses, suggesting that there was an issue with the request sent by the client, such as malformed syntax or unauthorized access.
* **500’s=** These status codes indicate server error responses, suggesting that there was an issue with the server processing the request, such as an unexpected condition or failure.
2. **What is a status code 202?** Status code 202 is "Accepted." It indicates that the request has been accepted for processing, but the processing has not been completed. It's often used for asynchronous processing where the server acknowledges receipt of the request and will handle it later.
3. **What is a status code 308?** Status code 308 is "Permanent Redirect." It indicates that the requested resource has been permanently moved to a new location. It informs the client to update the request URL with the new one provided in the response's Location header and redirect the future requests to that URL.
4. **What code would you use if an update didn’t return data to a client?** If an update operation didn't return any data to the client, you would typically use status code 204, "No Content." This status indicates that the server successfully processed the request but is not returning any content in the response.
5. **What code would you use if a resource used to exist but no longer does?** If a resource used to exist but no longer does, you would use status code 410, "Gone." This status indicates that the requested resource is no longer available at the server and there's no forwarding address. It's different from 404, which simply means the resource is not found.
6. **What is the ‘Forbidden’ status code?** The "Forbidden" status code is 403. It indicates that the server understood the request but refuses to authorize it. It's often used when the client doesn't have the necessary permissions to access the requested resource.

##
1. **Why do we need to pull our MongoDB database string out of our server and put it into our .env?** Pulling MongoDB database string into .env: This practice enhances security by keeping sensitive information like database connection strings out of code repositories, minimizing the risk of exposure.
2. **What is middleware?** Middleware functions are functions that have access to the request object (req), the response object (res), and the next middleware function in the application’s request-response cycle. They can modify the request and response objects or end the request-response cycle.
3. **What does app.use(express.json()) do?** This line of code configures Express to recognize incoming request objects as JSON. It parses the incoming request body, enabling easy access to JSON data within Express routes.
4. **What does the /:id mean in a route?*** This represents a route parameter in Express, allowing dynamic routing based on the value of the parameter. It captures the value specified in the URL and makes it available within the route handler.
5. **What is the difference between PUT and PATCH?** PUT is used to update or replace a resource entirely, while PATCH is used to partially update a resource. PUT typically requires sending the complete representation of the resource, while PATCH allows sending only the changes.
6. **How do you make a default value in a schema?** In schema definitions, default values can be set for fields. This ensures that if a value for a field is not provided during object creation, the default value will be used.
7. **What does a 500 error status code mean?** A 500 status code indicates an internal server error. It suggests that something has gone wrong on the server's end, and it is unable to fulfill the request. It's a generic error message, indicating an unexpected condition that prevented the server from fulfilling the request.
8. **What is the difference between a status 200 and a status 201?** A status code of 200 indicates a successful response to a request. It means the request has succeeded. On the other hand, a status code of 201 indicates that a new resource has been successfully created as a result of the request. It signifies successful creation, with the newly created resource being returned in the response body or headers.

## THings I want to know
