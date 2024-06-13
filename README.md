# docker setup for pokerogue

## requirements
* rogueserver has to be part of the root dir of this project
* you need to be able to pull from ghcr.io

## setup
1. clonse repo
2. make sure you fulfill requirements
3. execute `docker compose pull` -> `docker compose up --build -d`

## note
this setup usese my own forked client for pokerogue which is not always up to date      
you could easily clone the original frontend from their repo, add a Dockerfile and adjust the docker-compose accordingly so it builds from the Dockerfile instead of pulling my client
