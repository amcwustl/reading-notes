# Class 8 Reading Notes

This reading covers the best practices of API design which will be important as we build out back end applications.

## API Design Best Practices

- What does REST stand for?

> Representational State Transfer

- REST APIs are designed around a ____.

> A resource

- What is an identifier of a resource? Give an example.

> https://example.com/users/resource  
> Here resource would be the identifier of a resource.

- What are the most common HTTP verbs?

> The most common verbs are GET, POST, PUT, and DELETE

- What should the URIs be based on?

> URIS should be based on the resources they represent.  They should uniquely identify the resource.

- Give an example of a good URI.

> /customers/{id} would be a good URI because customers paths to the collection of customers and the id will path to a specific resource.

- What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?

> A chatty API means it requires multiple requests to perform a single operation.  This is generally a bad thing.

- What status code does a successful GET request return?

> 200 OK

- What status code does an unsuccessful GET request return?

> 404, 401, or 403.

- What status code does a successful POST request return?

> 201 Created

- What status code does a successful DELETE request return?

> 204 No Content

## Things I want to know more about

- What are some constraints that developers should consider when designing API's
- What is the syntax for accessing error messages on unsuccessful calls to an API.