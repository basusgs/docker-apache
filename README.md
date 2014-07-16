docker-apache
============

Dockerfile of CentOS 6, with HTTPD ITK, PHP 5.4, and ModSSL

docker run -d -i --name webserver -v `pwd`:/var/www/html -p 80 -e VIRTUAL_HOST=example.com -t avalawn/docker-apache

Note: Ensure your web accessible files are in public directory.
