# nginx-docker
A simple Nginx reverse-proxy that runs on Docker.

## docker build command
docker build . -t hello-nginx

## docker run command
docker run -d --net=host -p 22257:22257 hello-nginx
