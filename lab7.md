Question 0: What is the URL of your python flask_restfull code on github???

https://github.com/TurnipXenon/CMPUT404Lab7

Question 1: How are Flask and Django different? What does Django provide for you that Flask does not?

Flask is a lighter web framework compared to Django. Django provides a lot of features by default, like abstracting the database.

Question 2: What does REST stand for? When I say something is RESTful, what does that mean?

REST stands for Representational State Transfer. According to Red Hat (https://www.redhat.com/en/topics/api/what-is-a-rest-api), RESTful conforms to:

- managed through HTTP
- stateless client-server interactions
- a uniform interface

Question 3: What does CRUD stand for? For each letter in CRUD, give the associated HTTP method.

CRUD stands for Create, Read, Update, and Delete.

- Create = POST
- Read = GET
- Update = PUT
- Delete = DELETE

Question 4: What do HTTP 1XX Status Codes mean? HTTP 2xx? HTTP 3xx? HTTP 4xx? HTTP 5xx?

1XX is for informational responses;
2XX is for successful responses;
3XX is for redirection messages;
4xx is for client error responses; and
5xx is for server error responses

Question 5: What is an XSS attack? Provide one way a site can be vulneratble to an XSS attack.

According to Wikipedia, Cross-site attack or XSS attack is when attackers inject client-side scripts into the web pades viewed by other users. One example is allowing rich text formats and somehow letting users enter scripts in it. When other users see these posts, their browser may execute these scripts if not sanitized.

Question 6: What does CORS stand for? What situation in web application development will you need to implement CORS protection?

Accodring to MDN, is an HTTP-header based mechanism that allows a server to indicate any origins (domain, scheme, or port) other than its own from which a browser should permit loading resources. We might need to indicate other origins if we want to use resources from other origins, like keeping our images in another server, or getting posts from another node or server in our project.
