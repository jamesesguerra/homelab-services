FROM nginx:latest

WORKDIR /etc/nginx/conf.d

COPY config-files/* .

RUN mkdir /usr/share/nginx/html/dev && \
    mkdir /usr/share/nginx/html/uat