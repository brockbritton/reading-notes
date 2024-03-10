
# Reading 08 - API's

## Things I want to know more about

### API Design Best Practices

1. What does REST stand for?
- Representational State Transfer
2. REST APIs are designed around a **resource**.
3. What is an identifier of a resource? Give an example.
- URL
4. What are the most common HTTP verbs?
- Get, post, delete, patch
5. What should the URIs be based on?
- they should follow a predictable, hierarchical structure to enhance understandability and, therefore, usability.
6. Give an example of a good URI.
- host/customers/customerID/purchase
7. What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?
- They require you to have to do multiple calls to perform a single operation, which is generally seen as a bad thing
8. What status code does a successful GET request return?
- 200
9. What status code does an unsuccessful GET request return?
- 404
10. What status code does a successful POST request return?
- 200
11. What status code does a successful DELETE request return?
- 204