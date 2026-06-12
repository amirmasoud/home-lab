FROM nginx:1.27-alpine

RUN rm /etc/nginx/conf.d/default.conf
COPY cam-proxy.conf.template /etc/nginx/templates/cam-proxy.conf.template

EXPOSE 1984