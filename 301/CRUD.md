# CRUD


**Below you will find some reading material, code samples, and some additional resources that support today’s topic and the upcoming lecture.**



> Reading

### Status Codes Based On REST Methods

1. **In your own words, describe what each group of status code represents:**

.100’s = informational status codes

.200’s = success codes

.300’s = redirection codes

.400’s = client error codes

.500’s = server error codes


2. **What is a status code 202?**

Accepted 


3. **What is a status code 308?**

Permanent Redirect

4. **What code would you use if an update didn’t return data to a client?**

204 No Content

5. **What code would you use if a resource used to exist but no longer does?**

410 Gone 

6. **What is the ‘Forbidden’ status code?**

403 Forbidden

### sql vs nosql (Video)



1. **Why do we need to pull our MongoDB database string out of our server and put it into our .env?**

retrieve your database deployment's connection string. Whitelist your IP address to allow access to your Atlas cluster

2. **What is middleware?**

Middleware is software that provides common services and capabilities to applications outside of what's offered by the operating system

3. **What does app.use(express.json()) do?**

It parses incoming JSON requests and puts the parsed data in req.

4. **What does the /:id mean in a route?**

a section of Express code that associates an HTTP verb (GET, POST, PUT, DELETE, etc.), an URL path/pattern, and a function that is called to handle that pattern

5. **What is the difference between PUT and PATCH?**

PUT is amethod of modifying resource where the client sends data that updates the entire resource . PATCH is a method of modifying resources where the client sends partial data that is to be updated without modifying the 

6. **How do you make a default value in a schema?**

You can also set the default schema option to a function. Mongoose will execute that function and use the return value as the default

> Bookmark and Review

. [Status Codes Based On REST Methods](https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/)

. [Build A REST API With Node.js, Express, & MongoDB](https://www.youtube.com/channel/UCFbNIlppjAuEX4znoulh0Cw)


## Things I want to know more about

Nothing for today
