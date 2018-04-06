# Node-web-server  [![Build Status](https://travis-ci.org/Burlesque1/Node-web-server.svg?branch=master)](https://travis-ci.org/Burlesque1/Node-web-server)
A basic server using NodeJs. </br>
https://whispering-lake-98853.herokuapp.com/


How to run this app locally

1. Make sure nodeJS and MongoDB installed correctly

2. Clone the repo from github
```
git clone git@github.com:Burlesque1/Node-web-server.git
```

3. Install package dependencies
```
cd Node-web-server && npm install
```

4. Start MongoDB service 
```
~/bin/mongod --dbpath=<YOUR DBPATH>
```

5. Start server
```
node server/server.js
```

6. Open localhost:3001 in browser
