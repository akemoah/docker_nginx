# Version: 0.0.1
FROM scratch
MAINTAINER Arnauld KEMOAH "arnauldk@live.fr "
RUN apt-get update
RUN apt-get install -y nginx
RUN echo 'Default page. Nginx is in your container. ' \
>/usr/share/nginx/html/index.html
EXPOSE 8082
