# FROM openresty/openresty:alpine-fat
FROM dalongrong/pagespeed
COPY nginx.conf /usr/local/openresty/nginx/conf/
ADD index.html /usr/local/openresty/nginx/html/index.html
ADD index.css /usr/local/openresty/nginx/html/index.css
ADD app.png /usr/local/openresty/nginx/html/app.png
RUN mkdir -p /var/ngx_pagespeed_cache
EXPOSE 80
