# First Docker file

A javascript file containing simple console log

## How to build the docker image?

- Navigate to your directory
  `cd first-docker-file`
- Build the image using : docker build tag filepath  
  `docker build -t first-docker-file .`
- Checkout list of docker images using `docker images`
- Run it using `docker run first-docker-file`
- Run the container in shell mode `docker run -it first-docker-file sh`
