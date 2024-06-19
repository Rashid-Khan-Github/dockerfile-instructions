FROM nginx
RUN rm -rf /usr/share/nginx/html/index.html
ADD myfile.txt /tmp
ADD https://github.com/sivadevopsdaws74s/roboshop-documentation/blob/master/nginx.MD /tmp
ADD sample-1.tar /tmp







# LABEL add meta data to image such as owner, version etc.
# LABEL NAME="ALMA-NGINX"
# # For multiple labels, you can separate using forward slash
# LABEL OWNER=RASHID \
#       VERSION=8.0 \
#       DESCRIPTION="almalinux image"      
# EXPOSE 80/tcp
# ENV URL=http://docker.io USERNAME=spring
