FROM nginx:1.14.2-alpine

COPY ./config/docker/nginx/default.conf /etc/nginx/conf.d/default.conf
COPY app /app

CMD ["nginx", "-g", "daemon off;"]
