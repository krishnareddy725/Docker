FROM almalinux:8
RUN yum install -y nginx
RUN dwsample1-tar.tar /tmp/
CMD ["nginx", "-g", "daemon off -g;"]