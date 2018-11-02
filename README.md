## HTTP ROUTER 


## Features

1) Receive GET, POST, PUT and DELETE requests
2) Parse the Verb and URL from the request and match it a function
3) Build a response by executing the matching function
4) Return the response
Extension: Add wildcard support to URLS, so that it can understand e.g. "/peeps/{id}" and pass the id to the matching function
Extension: Add support cor CORS and OPTIONS requests.