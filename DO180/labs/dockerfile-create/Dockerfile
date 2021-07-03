FROM ubi7/ubi:7.7

MAINTAINER E Cabrera F enrique.cabflo@gmail.com

LABEL description="A custo Apache container based ond UBI 7"

RUN yum install -y httpd && \
    yum clean all

RUN echo "Hello from Dockerfile" > /var/www/html/index.html

EXPOSE 80 8180 9180 10080

CMD ["httpd","-D","FOREGROUND"]


