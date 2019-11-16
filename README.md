# spring-security

1. 

Authenication URL :http://localhost:8080/authenticate


Body :
{
  "username":"foo",
  "password":"foo"
}


Response : 

{

"jwt": "eyJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJmb28iLCJleHAiOjE1NzM5MTczNTQsImlhdCI6MTU3MzkxNzM1NH0.4A12wshGJ3-mX464QvcR_jHtKZz7izrniuka1iJ01OQ"

}

2. Resource URL : http://localhost:8080/hello
 Header 
  Authorization : 
    Bearer  eyJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJmb28iLCJleHAiOjE1NzM5Nzc4MjgsImlhdCI6MTU3MzkxNzgyOH0.OM8GJTpqRZsCDhJNDHvvUd0YrOCk5CYj1tthGMANcU8
 
 Response: Hello world
