FROM debian:buster-slim
RUN apt-get update && apt-get install nginx -y

EXPOSE 80
COPY teste1 /var/www/html/teste1
COPY teste2 /var/www/html/teste2
COPY teste3 /var/www/html/teste3

CMD ["nginx", "-g", "daemon off;"]