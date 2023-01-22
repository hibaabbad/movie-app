# Movie database app in NodeJS based on RedisGraph

## Technical Stack

- Frontend - _React_
- Backend - _Node.js_, _Redis_, _RedisGraph_

## How it works

The app consumes the data provided by the Express API and presents it through some views to the end user, including:
* Home page
* Sign-up and Login pages
* Movie detail page
* Actor and Director detail page
* User detail page


## Hot to run it locally?

### Prerequisites

- Node - v13.14.0
- NPM - v7.6.0

#### Write in environment variable or Dockerfile actual connection to Redis:

```
   REDIS_ENDPOINT_URL = "Redis server URI"
   REDIS_PASSWORD = "Password to the server"
```

### Local installation

Go to main folder and then:

```
# set redis data inside
.env

# install dependencies
npm install

# Run server
node app.js
```

#### Run client

cd client
yarn install
yarn start


