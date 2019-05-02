FROM nginx:1.14.2-alpine

COPY ./config/docker/nginx/default.conf /etc/nginx/conf.d/default.conf

RUN mkdir /app \
    && touch /app/index.php

CMD ["nginx", "-g", "daemon off;"]
