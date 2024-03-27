FROM nginx:1.25.4-alpine
EXPOSE 80 443
COPY certs/* /etc/nginx/ssl/localhost/
COPY config/localhost.conf /etc/nginx/nginx.conf
