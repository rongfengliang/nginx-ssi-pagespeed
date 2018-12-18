# nginx ssi demo with pagespeed

use openresty base image

## difference parts

```diff
+    pagespeed On;
+    pagespeed EnableFilters combine_css,combine_javascript;
```

## how to run

* build image

```code
docker-compose build
```

* running

```code
docker-compose up -d
```

## some images

![images](./images/QQ20181217-210845@2x.png)