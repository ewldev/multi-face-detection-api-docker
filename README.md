# Docker for Multi-face detection backend and Postgres database

Use docker compose to build and upload docker to AWS ECS

https://www.docker.com/blog/docker-compose-from-local-to-amazon-ecs/


1. Clone this repo
2. Run `npm install`
3. Add your own API key in the `controllers/image.js` file to connect to Clarifai API
4. Add your own database credentials to `server.js` line 12

Clarifai API key [here](https://www.clarifai.com/)

