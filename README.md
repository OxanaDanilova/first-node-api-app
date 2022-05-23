# First Node API Project

## Starter command
npm init -y
echo "node_modules/" > .gitignore
npm i axios
mkdir src
touch src/index.js

## package.json
"script":{
"start": "node src/index.js",
"deploy": "chmod +x src/index.js && npm link",
"undeploy": "npm unlink"
},
"bin": {
    "weather": "src/index.js"
  }