FROM docker.io/library/nginx:latest

RUN apt-get update && apt-get install -y curl iputils-ping

COPY nginx.conf /etc/nginx/nginx.conf

EXPOSE 8080
