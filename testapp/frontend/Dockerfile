FROM ubuntu:18.04
MAINTAINER pallavisv21@gmail.com
RUN apt-get -y update
RUN apt-get install -y nginx
ADD code /var/www/html
EXPOSE 80
ENV BACKENDLB=test
CMD ["nginx","-g","daemon off;"]

