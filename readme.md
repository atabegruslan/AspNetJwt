Swagger: https://localhost:7049/swagger/index.html

![](https://github.com/atabegruslan/AspNetJwt/assets/20809372/6a5ed26c-cf4f-4e2b-a189-0bc7d144d205)


Login
```
curl --location 'https://localhost:7049/api/User' \
--header 'Content-Type: application/json' \
--data '{
  "username": "string",
  "password": "string"
}'
```

Visit a protected page
```
curl --location 'https://localhost:7049/api/Home' \
--header 'Authorization: Bearer eyJhbG...' \
--data ''
```

## Tutorials

- https://medium.com/@vndpal/how-to-implement-jwt-token-authentication-in-net-core-6-ab7f48470f5c
  - https://github.com/vndpal/JwtInDotnetCore
- https://www.infoworld.com/article/3669188/how-to-implement-jwt-authentication-in-aspnet-core.html
