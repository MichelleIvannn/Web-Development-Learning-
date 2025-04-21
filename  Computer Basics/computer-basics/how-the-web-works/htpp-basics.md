# HTPP Basics

* HTTP uses a simple language of verbs to perform actions such as making requests.
* The HTTP [`GET`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Reference/Methods/GET) method is the one normally used to make HTTP requests of the type described above.

***

#### HTTP/2 200

* The version of HTTP that the server is using to send the response, in this case HTTP/2, followed by a [status code](https://developer.mozilla.org/en-US/docs/Web/HTTP/Reference/Status) indicating whether the request was successful. `200` indicates success.

#### Date, Expires, etc

* [HTTP headers](https://developer.mozilla.org/en-US/docs/Web/HTTP/Reference/Headers) containing additional information about the response (note that requests can have headers too), which provide extra information and/or modify its behavior

#### \<!doctype html>,etc

The response body, which in this case contains the MDN homepage's HTML document.

***

## Other status codes&#x20;

* Above, we met the `200` [status code](https://developer.mozilla.org/en-US/docs/Web/HTTP/Reference/Status), which indicates that the HTTP request was successful.

**301**

* The requested resource has been permanently moved to a new location, which is provided in the response.
* This is used for redirecting content when it's moved.

**400**

* The server can't process the request.
* This usually happens when the request isn't in a format the server understands, or has errors in it.

**404**

* The server cannot find the requested resource.
* This status is commonly returned if the URL is wrong or if content is deleted without putting a redirect in place.

**503**

* The request cannot be handled due to a problem with the server.
* This is common when servers are offline for maintenance, and it's expected to be temporary.
