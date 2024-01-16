FROM ubuntu:20.04

RUN apt-get update
RUN apt-get install -y nginx

RUN echo 'Hello les amis' > /var/www/html/index.html

VOLUME /var/log/nginx/


EXPOSE 80


CMD nginx -g "daemon off;"
