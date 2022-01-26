# Simple auth app using node.js, express.js and mongodb

- register new user and save in database
- login with user email and password and get token
- welcome route check token passed in header

#you need add token to POST request

[x-access-token-andrzej]

## Required

MongoDB installed on pc/cloud

API:

- /register
  `{ "first_name": "Andrzej", "last_name" : "Iwaniuk", "email" : "test@op.pl", "password" : "123456" }`

- /login
  `{ "email" : "test2@op.pl", "password" : "123456" }`

- /welcome (set token in header)
