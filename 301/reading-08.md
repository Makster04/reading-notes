# [Readings: APIs](https://github.com/codefellows/seattle-code-301d108/tree/main/class-08)


## [API Design Best Practices](https://learn.microsoft.com/en-us/azure/architecture/best-practices/api-design)

1. **What does REST stand for?** REST stands for Representational State Transfer.
2. **REST APIs are designed around a ____.** **REST APIs are designed around a resource.

3. **What is an identifier of a resource? Give an example.** An identifier of a resource is a unique reference to that resource. For example, in a RESTful API for managing books, an identifier for a specific book could be its ISBN number, like 978-0132350884.

4. **What are the most common HTTP verbs?** The most common HTTP verbs are GET, POST, PUT, PATCH, and DELETE.

5. **What should the URIs be based on?** URIs should be based on resources.

6. **Give an example of a good URI.** An example of a good URI could be /books/{book_id} where {book_id} is the identifier of a specific book, for example, /books/978-0132350884.

7. **What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?** Having a 'chatty' web API means that the API requires a large number of requests to perform a single operation due to fine-grained resources. This is generally considered a bad thing as it increases network overhead and reduces performance.

8. **What status code does a successful GET request return?** A successful GET request returns a status code 200 (OK).

9. **What status code does an unsuccessful GET request return?** An unsuccessful GET request returns a status code 404 (Not Found) if the resource is not found.

10. **What status code does a successful POST request return?** A successful POST request returns a status code 201 (Created).

11. **What status code does a successful DELETE request return?** A successful DELETE request returns a status code 204 (No Content).






## Things I want to know more about

  

