npm init -y    - for package-lock.json
npm install express.js    - for express.js
for creating multiple instances of the application we use docker

run the docker file and it will pop in the docker desktop
run on diffrent ports 
docker run -p 1111:7777 -d myserver
docker run -p 2222:7777 -d myserver
docker run -p 3333:7777 -d myserver