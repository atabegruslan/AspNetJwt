Swagger: https://localhost:7049/swagger/index.html

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
