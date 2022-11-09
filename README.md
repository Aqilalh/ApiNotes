# ApiNotes

An API is the tool that makes a website's data 
digestible for a computer. Through it, a computer can view and edit 
data, just like a person can by loading pages and submitting forms. 

When two systems (websites, desktops, smartphones) link up through 
an API, we say they are "integrated." In an integration, you have two 
sides, each with a special name. One side we have already talked about: 
the server. This is the side that actually provides the API.

Method 
The request method tells the server what kind of action the client wants 
the server to take. In fact, the method is commonly referred to as the 
request "verb." 
The four methods most commonly seen in APIs are: 
 • GET - Asks the server to retrieve a resource 
 • POST - Asks the server to create a new resource 
 • PUT - Asks the server to edit/update an existing resource 
 • DELETE - Asks the server to delete a resource
 
Headers 
Headers provide meta-information about a request. They are a simple 
list of items like the time the client sent the request and the size of the 
request body.

Body 
The request body contains the data the client wants to send the server. 
Continuing our pizza ordering example above, the body is where the 
order details go. 
A unique trait about the body is that the client has complete control 
over this part of the request. Unlike the method, URL, or headers, 
where the HTTP protocol requires a rigid structure, the body allows the 
client to send anything it needs.

Basic Authentication
Basic Auth only requires a username and password. The client takes 
these two credentials, smooshes them together to form a single value 1, 
and passes that along in the request in an HTTP header called 
Authorization.

API Key Authentication 
API Key authentication is a technique that overcomes the weakness of 
using shared credentials by requiring the API to be accessed with a 
unique key.

• SOAP: API architecture known for standardized message formats 
 • REST: API architecture that centers around manipulating 
resources 
 • Resource: API term for a business noun like customer or order 
 • Endpoint: A URL that makes up part of an API. In REST, each 
resource gets its own endpoints 
 • Query String: A portion of the URL that is used to pass data to the 
server 
 • Query Parameters: A key-value pair found in the query string 
(topping=cheese) 
 • Pagination: Process of splitting up results into manageable 
chunks

REST APIs use the query string to define details of a search. These 
details are called query parameters. The API dictates what parameters 
it will accept, and the exact names of those parameters need to be used 
for them to effect the search. 







