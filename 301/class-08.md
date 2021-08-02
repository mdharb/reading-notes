# **APIs**

## API Design Best Practices

1. **What does REST stand for?**
   * Representational State Transfer

***

2. **REST APIs are designed around a** `resources`.

***

3. **What is an identifer of a resource? Give an example.**
   *  is a URI that uniquely identifies that resource.
      * ```https://locationiq.com/docs```

*** 

4. **What are the most common HTTP verbs?**
   * GET, POST, PUT, PATCH, and DELETE.

***

5. **What should the URIs be based on?**
   * 

***

6. **Give an example of a good URI.**
   * ```https://adventure-works.com/orders```

***


7. **What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?**
   * ```https://adventure-works.com/create-order```

***

8. **What status code does a successful `GET` request return?**
   * HTTP status code 200 (OK). 

***

9. **What status code does a unsuccessful `GET` request return?**
   * 404 (Not Found).

***

10. **What status code does a successful `POST` request return?**
    * HTTP status code 201 (Created).

***

11. **What status code does a successful `DELETE` request return?**
    * HTTP status code 204 (No Content).