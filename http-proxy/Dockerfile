FROM nginx:latest
 
RUN apt-get update && apt-get install -y \
    openssl \
    ssl-cert \
    && apt-get clean \
    && rm -rf /var/lib/apt/lists/*
 
COPY ./conf.d/ssl.conf /etc/nginx/conf.d/

EXPOSE 443