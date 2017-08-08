# nginx-docker
A simple Nginx reverse-proxy that runs on Docker.

This will listen on port 22257 and will forward it to port 33357 listening on the localhost.

## docker build command
docker build . -t hello-nginx

## docker run command
docker run -d --net=host -p 22257:22257 hello-nginx
