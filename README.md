# introToAPIs
FOR THE DOG API

NAME: age, VALUE: 0

The value represents the number of seconds the the object, in this case some code redirecting to a random image of a dog, was in the proxy cache. It's 0, which makes sense because the image was just fetched.

NAME: Content-type, VALUE: application/json

The value represents the type of content of the request that the application sent. JSON is a file format that stores readable text. The application transfers the information from its native language into oa JSON file and sends it in their response. JSON is easy to read and is broadly used.  

NAME: accept-ranges, VALUE: bytes

If the application receives a request, this value represents the amount of data the application will send when the data has to be broken up into parts. It's the maximum amount of data you can request from the server at a time when you're data is partialized.

NAME: x-powered-by, VALUE: PHP/7.3.17

This is the Backend powering the application. It might be the language that saved the data to the JSON file, unless that was done on the front end in Javascript (which would make sense since JSON was derived from Javascript). It's a custom header, which means they specified the language. That would make sense the JSON files were generated in Javascript. They have to specify the backend because their front-end is talking to the internet/other computers. I'm speculating, but it remains true that they had to say that their backend was written in C#. 
