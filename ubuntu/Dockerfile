FROM ubuntu:16.04

LABEL maintainer="kritsadanshon.s@tangerine.co.th"

RUN apt-get update \
    && apt-get install -y nginx \
    && apt-get clean \
    && rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/* \
    && echo "daemon off;" >> /etc/nginx/nginx.conf

COPY index.html /var/www/html

EXPOSE 80

CMD ["nginx"]
