FROM almalinux:8
RUN yum install nginx -y 
# EXPOSE is not adding any functionality, this is just for information
EXPOSE 80/tcp
# daemon off command makes our container running and attached to screen
CMD [ "nginx", "-g", "daemon off;" ]