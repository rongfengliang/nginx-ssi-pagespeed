# FROM openresty/openresty:alpine-fat
FROM dalongrong/pagespeed
# COPY nginx.conf usr/local/openresty/nginx/conf/
# ADD index.html /usr/local/openresty/nginx/html/web1/index.html
# ADD index.css /usr/local/openresty/nginx/html/web1/index.css
RUN mkdir -p /var/ngx_pagespeed_cache
COPY nginx.conf /etc/nginx/
ADD index.html /usr/share/nginx/html/index.html
ADD index.css /usr/share/nginx/html/index.css
ADD app.png /usr/share/nginx/html/app.png
EXPOSE 80
