# CRUD

1. **In your own words, describe what each group of status code represents:**
   * 100’s = 
        * These are informational status codes; they usually tell the client that the header part of the request has been received and the server will try to comply with a transmission demand of the client.

   * 200’s =
        * These are the success codes. They tell the client that its request was accepted. 

   * 300’s =
        * These are redirection codes. They tell the client that the resource they are requesting isn’t available at the expected location anymore.

   * 400’s =
        * These are the client error codes. They are all about invalid requests a client sent to a server.

   * 500’s =
        * These are the server error codes. Often they indicate problems with overwhelmed servers or unreachable servers behind proxies, but sometimes they can be directly related to client requests that trigger error exceptions on the server.

2. **What is a status code 202?**
   * Often used for asynchronous processing. This code tells the client that the request was valid, but its processing will finish sometime in the future.

3. **What is a status code 308?**
   * his tells the client to use another URL to access the resource and not use the current URL anymore. 

4. **What code would you use if an update didn’t return data to a client?**
   * 204 No Content.

5. **What code would you use if a resource used to exist but no longer does?**
   * 308 Permanent Redirect.

6. **What is the ‘Forbidden’ status code?**
   * 403 Forbidden.

***

## Build A REST API With Node.js, Express, & MongoDB.

1. **What is middleware?**
   * Is a function that will receive the Request and Response objects

2. **What does app.use(express.json()) do?**
   * is a method inbuilt in express to recognize the incoming Request Object as a JSON Object.

3. **What does the /:id mean in a route?**
   * 

4. **What is the difference beween PUT and PATCH?**
   * PUT method uses the request URI to supply a modified version of the requested resource which replaces the original version of the resource, whereas the PATCH method supplies a set of instructions to modify the resource.

5. **What does a 500 error status code mean?**
   * Internal Server Error server error response.

6. **What is the difference between a status 200 and a status 201?**
   * 200 OK success status response code indicates that the request has succeeded.
   * 201 Created success status response code indicates that the request has succeeded and has led to the creation of a resource.
