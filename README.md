# BuyBecho - It's more than eBay to us !

## About this Project

Due to lack of communication between students of a university, many individual resources
are not efficiently shared. For example books, notes, coolers, mattresses or other
necessary items remain unused when it could have been given to others who needed
them. Aim of this project is to build a platform where different students from the same
university can contact each other for sharing the products that they no longer need.The
portal serves as a bridge to connect the buyer and seller among the student community.

--------------

## Quick Start

### Installation step
``` bash
# Install dependencies for client
yarn 

# Install dependencies for server
yarn server-install

# Run the client & server with concurrently
yarn dev

# Run the JSON-Server server only
yarn server

# Run the React client only
yarn client

# Server runs on http://localhost:3000 and client on http://localhost:1234
```

### Changes 

- on `src/Config.js` file: Change to server url
```
    module.exports = {
        BACKEND_URL: "http://localhost:3000",
    };
```
- on `src/firebase/firebase.js` file: Change to firebase storege api keys
```
  apiKey:"",
  authDomain:"",
  databaseURL: "",
  projectId: "",
  storageBucket: "",
  messagingSenderId: "",
  appId: "",
```
--------------

# Development

Following `Tech Stack` would help me to build this prototype:
- Frontend Library : [React.js](https://reactjs.org/)
- UI Library: [Chakra UI](https://chakra-ui.com/)
- Image Storage : [Firebase Storage](https://firebase.google.com/docs/storage/web/start)
- Server : [JSON Server](https://www.npmjs.com/package/json-server)
- Deployment : [Vercel](http://vercel.com/)
