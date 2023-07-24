# INTRODUCTION TO APIs

## APIs

* Application Programming Interface - (API) is a software intermediary that allows two applications to talk to each other. APIs are used to allow different software applications to communicate and share data.

### Types of APIs

* Local APIs - These are APIs that are hosted on your local machine and are not available to the public. They are used to communicate between different processes running on the same machine.

* Web APIs - These are APIs that are hosted on a remote server and can be accessed over the internet. They are used to communicate between different processes running on different machines.

* Program APIs - These are APIs that are built into a program to allow other programs to communicate with it. They are used to communicate between different processes running on the same machine.

## REST APIs

### What is REST API?

* REST stands for Representational State Transfer. It is an architectural style for designing APIs. It is not a standard but a set of constraints that must be followed to be considered a REST API.

### REST API Methods

#### GET Request

* GET requests are used to retrieve data from the server. They are the most common type of request. They are also the simplest type of request. They can be used to retrieve data from a database, a file, or any other source of data.

#### POST Request

* POST requests are used to send data to the server. They are used to create new resources on the server. They are also used to update existing resources on the server. They are also used to delete existing resources on the server.

#### PUT Request

* PUT requests are used to update existing resources on the server. They are used to update existing resources on the server. They are also used to delete existing resources on the server.

#### DELETE Request

* DELETE requests are used to delete existing resources on the server. They are used to delete existing resources on the server. They are also used to delete existing resources on the server.

### What Makes a Request

1. Endpoint - Is the URL

```bash
https://api.example.com/v1/users
```

2. Method - Is the type of request

```javascript
fetch('https://api.example.com/v1/users', {
  method: 'GET' // GET, POST, PUT, DELETE
})
```

3. Headers - Are used to provide additional information about the request

```javascript
fetch('https://api.example.com/v1/users', {
  method: 'GET',
  headers: {
    'Content-Type': 'application/json'
  }
})
```

4. Data - Is the data that is sent with the request

```javascript
fetch('https://api.example.com/v1/users', {
  method: 'POST',
  headers: {
    'Content-Type': 'application/json'
  },
  body: JSON.stringify({
    name: 'John Doe',
    email: 'johindoe@gmail.com'
    })
})
```

### HTTP Status Codes

* 200+ - Success

* 300+ - Redirection (Means that the resource has been moved)

* 400+ - Client Error

* 500+ - Server Error

### Consuming APIs

* To consume an API, you need to make a request to the API and then parse the response.
* Web applications use the Fetch API to make requests to APIs. Axios is a popular library that makes it easier to make requests to APIs.

