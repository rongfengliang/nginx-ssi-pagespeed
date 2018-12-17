# FROM openresty/openresty:alpine-fat
FROM pagespeed/nginx-pagespeed
# COPY nginx.conf usr/local/openresty/nginx/conf/
# ADD index.html /usr/local/openresty/nginx/html/index.html
# ADD index.css /usr/local/openresty/nginx/html/index.css
COPY nginx.conf /etc/nginx/
ADD index.html /usr/share/nginx/html/index.html
ADD index.css /usr/share/nginx/html/index.css
EXPOSE 80
