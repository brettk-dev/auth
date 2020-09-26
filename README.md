# Auth

This is a simple auth microservice.

## Create an account (POST /register)

Example payload

```json
{
  "email": "you@example.com",
  "password": "SuPeRsEcUrE!",
  "name": "You"
}
```

Example response

```json
{
  "errors": []
}
```

## Login (POST /login)

Example payload

```json
{
  "email": "you@example.com",
  "password": "SuPeRsEcUrE!",
}
```

Example response

```json
{
  "errors": [],
  "token": "abcd..."
}
```

## Logout (GET /logout)

Example response

```json
{
  "errors": []
}
```

## [INTERNAL] Verify Token (GET /verify)

Example response

```json
{
  "errors": []
}
```
