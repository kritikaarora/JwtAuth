# What is JWT?
  JWT stands for JSON Web Token and it is one of  authentication method  used by client/server applications where the client is a Web application using JavaScript and some frontend framework like Angular, React or VueJS.

# How JWT Works?
The JWT is just an authorization token that should be included in all requests:

```linux
curl http://127.0.0.1:8000/protected-route/ -H 'Authorization: Bearer eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJ0b2tlbl90eXBlIjoiYWNjZXNzIiwiZXhwIjoxNTQzODI4NDMxLCJqdGkiOiI3ZjU5OTdiNzE1MGQ0NjU3OWRjMmI0OTE2NzA5N2U3YiIsInVzZXJfaWQiOjF9.Ju70kdcaHKn1Qaz8H42zrOYk0Jx9kIckTn9Xx7vhikY'

```
The JWT is acquired by exchanging an username + password for an access token and an refresh token.

The access token is usually short-lived (expires in 5 min or so, can be customized though).

The refresh token lives a little bit longer (expires in 24 hours, also customizable). It is comparable to an authentication session. After it expires, we need a full login with username + password again.

Jwt   token is composed by three parts:
header.payload.signature

# Register api 
[Link](http://127.0.0.1:8000/api/auth/register)

# Lgin api 
[Link](http://127.0.0.1:8000/api/auth/register)


