FROM almalinux:8
RUN yum install -y nginx
ADD sample-1.tar /tmp/
CMD ["nginx", "-g", "daemon off;"]