FROM nginx

RUN rm /etc/nginx/conf.d/default.conf
COPY nginx/nginx.conf /etc/nginx/
COPY nginx/proxy.conf /etc/nginx/conf.d/
COPY https/ /etc/nginx/certs/