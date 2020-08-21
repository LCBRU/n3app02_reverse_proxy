FROM nginx
LABEL maintainer="Richard Bramley <rabramley@gmail.com>"

RUN echo "2020-08-21 A"

RUN rm /etc/nginx/conf.d/default.conf
ADD sites-enabled/ /etc/nginx/conf.d/
ADD cert /cert
