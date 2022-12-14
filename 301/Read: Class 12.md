### Status Codes Based On REST Methods

1. Status code

* 100’s -  Tells the client when part of their request was received and will attempt to comply with a transmission demand of the client.
* 200’s - is when the client request was approved. But 202 means that only the request has met the validation requirements.
* 300’s - is when the clients request is not available and may be held somewhere else.
* 400’s - is when the client as made an error like wrong url.
* 500’s - is when there is an error from the server when it is overwhelmed.

2. 202 is when the request has met the validation requirements.
3. Status code 308 tells the client to use another URL to access the resource and not use the current URL anymore. It’s helpful when we have multiple endpoints for one resource, but don’t want to implement reading from all of them.
4. You should use 204 No Content if an update didn’t return data to a client.
5. You should use 410 Gone if a resource used to exist but no longer does.
6. The Forbidden status code is when the client has authorized or doesn’t need to authorize itself, but still has no permissions to access the resource.

### Build A REST API With Node.js, Express, & MongoDB - Quick

1. We need to pull our MongoDB database string out of our server and put it into our .env because when it time to deploy our work we want to avoid using localhost.
2. Middleware is when code that goes through the server receives a request before getting to the routes.
3. app.use(express.json()) allows the serve to use json.
4. /:id is a perimeter request.
5. PUT takes all the information and updates it. While PATCH will only update the user input.
6. You make a default value in a schema by using default.
7. 500 error status code means that are error codes from the server.
8. Status 200 is It’s the basic status code to tell the client everything went good. Since we don’t create endpoint accessible resource when creating an access token, we can use 200 as a status for that action. Status 201 The most fitting for Create operations. This code should signal backend-side resource creation and come along with a Location header that defines the most specific URL for that newly created resource. It’s also a good idea to include appropriate representation of the resource or at least one or more URLs to that resource in the response body.

### Things I want to learn more about

1. MongoDB database.
