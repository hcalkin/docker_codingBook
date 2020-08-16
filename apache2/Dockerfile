FROM centos
RUN  yum install httpd unzip -y 
ADD  https://github.com/mdn/beginner-html-site-styled/archive/gh-pages.zip /var/www/html/code.zip
RUN  cd /var/www/html/ && unzip code.zip && mv /var/www/html/beginner-html-site-styled-gh-pages/*  /var/www/html/
CMD  apachectl -DFOREGROUND