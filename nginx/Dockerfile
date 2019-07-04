FROM nginx
LABEL maintainer="Richard Bramley <rabramley@gmail.com>"

RUN rm /etc/nginx/sites-enabled/default
ADD sites-enabled/ /etc/nginx/sites-enabled/
ADD cert /cert