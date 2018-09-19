## run server:
npm run start


## run backend server 

nodemon backend/server.js



## Requirement 

npm i react react-dom

npm i -D webpack webpack-dev-server cross-env

npm i -D babel-loader babel-core babel-preset-es2015 babel-preset-react


# package.json
dev  cross-env NODE_ENV=development webpack-dev-server --hot

build  cross-env NODE_ENV=production webpack


# webpack.config.js

const path = require('path')
let config = {
	
}

module.exports = config

# .balelrc

{
	"presets" : ["es2015", "react"]
}
