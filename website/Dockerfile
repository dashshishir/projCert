FROM devopsedu/webapp
WORKDIR /var/www/html
ADD . .
RUN rm -f /var/www/html/index.html
CMD apachectl -D FOREGROUND