FROM centos
RUN  yum install httpd  -y 
COPY html-code /var/www/html/
CMD  apachectl -DFOREGROUND
