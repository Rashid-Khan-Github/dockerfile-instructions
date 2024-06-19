FROM almalinux:8
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
RUN echo "Hi, This is the Docker World" > /usr/share/nginx/html/index.html
ENTRYPOINT [ "nginx", "-g", "daemon off;" ]


# LABEL add meta data to image such as owner, version etc.
# LABEL NAME="ALMA-NGINX"
# # For multiple labels, you can separate using forward slash
# LABEL OWNER=RASHID \
#       VERSION=8.0 \
#       DESCRIPTION="almalinux image"      
# EXPOSE 80/tcp
# ENV URL=http://docker.io USERNAME=spring
