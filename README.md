# NodeRESTapi
NODE REST API to create json files for users, tokens and checks

## Run
With node in your machine run this command in the root folder of the app to start the server
```bash
node index.js
```

## POST: Create a User
Server: localhost:3000/users

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
