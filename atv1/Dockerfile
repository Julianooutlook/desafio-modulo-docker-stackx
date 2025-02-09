FROM nginx:alpine

WORKDIR /app

COPY index.html /app/index.html

ENV APP_VERSION=1.0.0

RUN apk add --no-cache curl htop wget

RUN rm /etc/nginx/conf.d/default.conf

COPY nginx.conf /etc/nginx/conf.d/default.conf

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]
