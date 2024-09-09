FROM almalinux:8
RUN yum install -y nginx
ADD dwsample1-tar.tar /tmp/
CMD ["nginx", "-g", "daemon off -g;"]