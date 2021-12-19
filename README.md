# Node Hello World

Simple node.js app that servers "hello world"

Great for testing simple deployments to the cloud

## Run It

`npm start`

Build docker image:
docker build -t node-hello .

Run app on port 80:
docker run -d -p 80:3000 node-hello
