# Marko.js UI Twitter API consumer
Source codes for a User Interface built with [Marko.js](https://markojs.com/) and [MaterializeCSS](http://materializecss.com/) which consumes a API built with [Express.js](http://expressjs.com/) and the npm plugin: [twitter](https://www.npmjs.com/package/twitter) that requests data from [Twitter API](https://developer.twitter.com/en/docs/api-reference-index).

Live at: https://marko-twitter-api-paodlkdbyp.now.sh/ hosted by [Zeit.co](https://zeit.co/)

## Local ussage

### 1) Prepare the local server
Clone and start the local server: https://github.com/sorcamarian/markojs-twitter-api-server
```bash
git clone https://github.com/sorcamarian/markojs-twitter-api-server.git
cd markojs-twitter-api-server
npm install
```
NOTE: Update the Twitter credentials from [server.js#L12](https://github.com/sorcamarian/markojs-twitter-api-server/blob/master/index.js#L12)
```bash
node index.js
```
Result of current `/dist` codes can be seen on http://localhost:7070/

### 2) Start Marko.js
Clone this repository and start Marko
```bash
git clone https://github.com/sorcamarian/markojs-twitter-api.git
cd markojs-twitter-api
npm install
npm start
```

Live User Interface changes can be seen on http://localhost:8080/


---

# Build with Marko Starter Demo
This repo demos the basic features of [`marko-starter`](https://github.com/marko-js/marko-starter).
