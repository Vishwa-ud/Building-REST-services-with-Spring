# Building-REST-services-with-Spring

run = ./mvnw spring-boot:run

# USER Crud Operation

http://localhost:8080/
Hello Vishwa

```
POST http://localhost:8080/api/users
```
test data

{
  "id": 1,
  "name": "John Doe",
  "email": "john.doe@example.com"
}
Read
```
GET http://localhost:8080/api/users
```
Update
```
PATCH  http://localhost:8080/api/users/1
```
Delete
```
Delete http://localhost:8080/api/users/1
```