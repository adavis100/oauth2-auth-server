This project is the result of several hours of investigation into setting up an OAuth2 authorization server using Spring Security.

To obtain a JWT access token:
```
curl -X POST --user 'foo:fooSecret' -d 'grant_type=password&username=user&password=password' http://localhost:9000/oauth/token
```
