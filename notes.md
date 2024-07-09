# Dockerfile

for `/api`:

Build the image: `docker build --no-cache -t simple-api:nodemon .`
toggle `no-cache` ?

Run a container: `docker run --name simple-nodemon -p 4000:4000 --rm -v /Users/adamnyx/Desktop/spaceship/api/app:/app -v /app/node_modules simple-api:nodemon`
`rm` to auto-delete when stopping


# Docker-compose
