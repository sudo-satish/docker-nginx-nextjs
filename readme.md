### Description
Write nginx configuration in nginx.conf


### Build image
docker build --tag autouw-nginx .

### Delete image
docker image rm autouw-nginx

### Delete container
docker container rm autouw-nginx -f

### Run container
docker run -d -p 80:80 --name autouw-nginx autouw-nginx
