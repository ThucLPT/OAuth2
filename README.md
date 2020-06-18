Multi-module OAuth2 authorization_code flow sample (Authorization Server + Resource Server, client is Postman since redirect_uri in Authorization Server belong to Postman) using Spring Boot and ` spring-security-oauth2-autoconfigure` dependency.
- Run Authorization Server: `mvnw -f auth-server spring-boot:run`
- Run Resource Server: `mvnw -f resource-server spring-boot:run`
- Get access token: Open Postman -> Authorization -> Type -> OAuth 2.0 -> Get New Access Token -> Request Token
##### Ref:
[https://projects.spring.io/spring-security-oauth/docs/oauth2.html](https://projects.spring.io/spring-security-oauth/docs/oauth2.html)

[https://docs.spring.io/spring-security-oauth2-boot/docs/current/reference/html5/](https://docs.spring.io/spring-security-oauth2-boot/docs/current/reference/html5/)