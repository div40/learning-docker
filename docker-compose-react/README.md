# Docker Compose

Tool for defining and running multi container application

## How it works?

- Use command `docker init` and select the options

- After going through it, it will automatically create three files

1. Dockerfile
2. compose.yaml
3. .dockerignore

- Then use command `docker compose up` (run as admin if permission denied error comes up)

This is still not optimal developer experience as we have to rerun the container whenever any change is made to package.json
