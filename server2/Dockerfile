FROM ubuntu
RUN apt-get update && apt-get install -y apache2 && apt-get install -y vim && apt-get install -y curl

CMD ["/usr/sbin/apache2ctl", "-D", "FOREGROUND"]