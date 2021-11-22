Login API Walkthrough: 

POST FOR SIGNUP

{
    "username": "moderator1",
    "email": "moderator@gmail.com",
    "password":"password@1234",
    "roles": ["user", "moderator"]
}

SIGN-IN: http://localhost:8080/api/auth/signin

{
    "username": "moderator1",
    "password":"password@1234"
   
}

Collect x-access-token, and GET http://localhost:8080/api/test/user. Pass value of x-access-token and see User Specific content.

Show user specific end-point.  : Likewise GET http://localhost:8080/api/test/admin OR GET GET http://localhost:8080/api/test/mod

Try wrong password. 






