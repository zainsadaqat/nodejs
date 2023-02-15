# Nodejs

## What is NodeJS
NodeJS is javascript runtime environment;


## Parsing incoming data
data coming in the form request is actually a stream of data.

### Streams & Buffer
The request that node receives is in the form of chunks e.g., Request Body Part1, Request Body Part2, Request Body Part3 .... Fully Parsed. 
So that we don't have to wait for the full request to be parsed and we could start working on the chunks independently. 
Also node doesn't know in advance how complex and big the request is.
But we can't arbitrarily try working on those chunks that is why to organise this we use Buffer.
A Buffer is like a bus stop. Buses are always driving but they do stop to pass and receive the passengers.
A Buffer allows you to hold multiple chunks and work with them before they are released once you're done.

## JavaScript on the Server
- We can use NodeJS to write Server Side Code
### Run Server:- Create server and listen to incoming requests and send response to that requests.
- We use NodeJS for Business Logic like Handling Requests, Validate inputs, Connect to Database.

### Side Note:- Using NodeJS, You're not just limited to the Server

### NodeJS is single threaded
