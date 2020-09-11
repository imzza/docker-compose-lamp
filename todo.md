* Update japanese Readme
* Update issue templates
* php8 as soon as it is available


docker run --rm httpd:alpine cat /usr/local/apache2/conf/httpd.conf > my-httpd.conf
docker run -dit --name my-apache-app -p 8080:80  httpd:alpine
run command in container
docker exec -it dfb2f546716a /bin/sh
