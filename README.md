# NodeRESTapi
NODE REST API to create json files for users, tokens and checks


## POST: Create a User
server: localhost:3000/users

Header: Content-Type: application/json

Body:
```js
{
 "firstName": "Joe",
 "lastName": "Doe",
 "phone": "5554444333",
 "password": "joeDoePassword",
 "tosAgreement": true
}
```
