FROM alpine:3.17

# WORKDIR /usr/share/nginx/html

RUN apk update && apk add --no-cache nginx openssl

# COPY nginx.conf /etc/nginx/nginx.conf

EXPOSE 443:443

CMD ["nginx", "-g", "daemon off;"]