# FROM openresty/openresty:alpine-fat
FROM dalongrong/pagespeed
# COPY nginx.conf usr/local/openresty/nginx/conf/
# ADD index.html /usr/local/openresty/nginx/html/index.html
# ADD index.css /usr/local/openresty/nginx/html/index.css
RUN mkdir -p /var/ngx_pagespeed_cache
COPY nginx.conf /etc/nginx/
ADD index.html /usr/share/nginx/html/index.html
ADD index.css /usr/share/nginx/html/index.css
EXPOSE 80
