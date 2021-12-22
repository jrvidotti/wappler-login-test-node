###
POST http://localhost:8100/api/auth/register
Content-Type: application/json

{
  "email": "test@test.com",
  "password": "123456"
}

###
POST http://localhost:8100/api/auth/login
Content-Type: application/json

{
  "email": "test@test.com",
  "password": "123456"
}

# >>> NOT AUTHORIZED
