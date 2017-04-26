# nginx
nginx based on alpine linux


## Deploy on Openshift (minshift)
oc new-app https://github.com/jpduyx/nginx.git && oc expose service nginx && oc logs -f bc/nginx
