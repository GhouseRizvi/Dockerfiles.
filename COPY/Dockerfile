FROM almalinux
RUN yum install nginx -y
CMD [ "nginx","-g","daemon off;" ]
RUN rm -f /usr/share/nginx/html/index.html
COPY qi /usr/share/nginx/html