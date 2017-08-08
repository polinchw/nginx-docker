# nginx-docker
A simple Nginx reverse-proxy that runs on Docker.

This will listen on tcp port 22251 and will forward it to port 33351 listening on the localhost.
This will listen on http port 22257 and will forward it to port 33357 listening on the localhost.

## docker build command
docker build . -t hello-nginx

## docker run command
docker run -d --net=host -p 22251:22251 -p 22257:22257 hello-nginx
