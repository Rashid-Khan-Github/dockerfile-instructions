FROM almalinux:8
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
RUN echo "Hi, This is the Docker World" > /usr/share/nginx/html/index.html
CMD [ "nginx", "-g", "daemon off;" ]
