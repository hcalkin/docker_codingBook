FROM centos
RUN  yum install httpd unzip -y 
ENV  HTML beginner-html-site-styled
WORKDIR /var/www/html/
ADD  https://github.com/mdn/$HTML/archive/gh-pages.zip ./code.zip
RUN  unzip code.zip && mv ./$HTML-gh-pages/*  .
CMD  apachectl -DFOREGROUND