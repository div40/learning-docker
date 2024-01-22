## React Docker demo

Dockerizing a basic vite react app

## How to build the docker image?

- Navigate to your directory
  `cd react-docker`
- Build the image using : docker build tag filepath  
  `docker build -t react-docker .`
- Run it using port mapping `docker run -p 5173:5173 react-docker`
- Enable live editing using `docker run -p 5173:5173 -v "$(pwd):/app" -v /app/node_modules react-docker`

## Publish the image

- Publish the docker image using `docker tag <filename> <docker_username/image_name>` (remove <>)
- Push the image using `docker push <docker_username/image_name>`
