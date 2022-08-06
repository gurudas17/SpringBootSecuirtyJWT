# SpringBootSecuirtyJWT
Code is taken reference from https://www.bezkoder.com/spring-boot-login-example-mysql/

To test the flow use below url and body text. Use postman and use Content type as application -json and method type is post 
1) Sign up flow

URL - http://localhost:8080/api/auth/signup
Body having below json data
{
"username":"mod",
"email":"mod@gmail.com",
"password":"123456",
"role":["user","mod"]
}

2) Sign in flow
URL http://localhost:8080/api/auth/signin
Body data-
{
"username":"mod",
"password":"123456"
}
