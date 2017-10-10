FROM ubuntu:16.04

RUN apt-get update && apt-get install -y nginx && apt-get install -y vim && apt-get install -y curl

RUN rm /etc/nginx/sites-enabled/default

CMD ["nginx", "-g", "daemon off;"]