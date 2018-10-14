# nginx
# Version: 0.0.1
FROM ubuntu:14.04
MAINTAINER James Turnbull "1220818581@qq.com"
RUN apt-get update
RUN apt-get install -y nginx
RUN apt-get install -y vim
RUN echo '<h1>hello,welcome to docker_nginx!</h1>' > /usr/share/nginx/html/index.html
