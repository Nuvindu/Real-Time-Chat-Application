# Real-Time-Chat-Application
Chat Application with Instant Messaging feature. Technologies - React, GraphQL, WebSockets

<br/>

### Dependencies

<br/>

#### Server

<br/>

Create new package 
```javascript
npm init -y
```

GraphQL Yoga (A Fully-featured GraphQL Server):  
```javascript
npm install graphql-yoga 
 ```

<br/>

#### Client

<br/>


If yarn package is not yet installed, refer the this [link](https://classic.yarnpkg.com/lang/en/docs/install) to install it.


Create new package: 
```javascript 
yarn init -y 
```

**If a yarn command is not working, try using the following command:**

```javascript
powershell -ExecutionPolicy Bypass -File 'C:\Users\ {Your User Account Name} \AppData\Roaming\npm\yarn.ps1' {yarn command} 
 ```

Apollo Client: 
```javascript
yarn add @apollo/client graphql 
```

Chakra UI: 
```javascript
yarn add @chakra-ui/react @emotion/react@^11 @emotion/styled@^11 framer-motion@^5 
 ```

WebSocket: 
```javascript
yarn add subscriptions-transport-ws 
 ```

Shrads React: 
```javascript
yarn add shards-react 
```

<br/>

### Guide

<br/>

Enter to the server folder from a terminal and start the server

 ```javascript
npm start 
  ```

While the server running, create another terminal and enter to the client folder and start the React app

```javascript
yarn start 
```


<br/>

### References 

<br/>

https://www.apollographql.com/docs/react/get-started

https://www.youtube.com/watch?v=E3NHd-PkLrQ

https://github.com/jherr/chat-o-matic
