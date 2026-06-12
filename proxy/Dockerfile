FROM nginx:1.27-alpine

RUN rm /etc/nginx/conf.d/default.conf
COPY proxy.conf.template /etc/nginx/templates/proxy.conf.template

ENV LISTEN_PORT=8080