FROM nginx:1.19.0-alpine
RUN mkdir /app
RUN rm /etc/nginx/conf.d/default.conf
COPY banana.example.com.conf /etc/nginx/conf.d/
WORKDIR /app
