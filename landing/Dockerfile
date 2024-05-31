FROM nginx:1

COPY /src/* /usr/share/nginx/html

COPY nginx/nginx.conf /etc/nginx/conf.d/default.conf
COPY nginx/nginx-backend-not-found.conf /etc/nginx/extra-conf.d/backend-not-found.conf
