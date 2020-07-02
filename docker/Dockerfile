FROM centos:7
RUN yum -y install epel-release
RUN yum -y update
RUN yum -y install nginx
RUN yum clean all
RUN rm -rf /usr/share/nginx/html/*
RUN echo "File timestamp is : $(date). in your company." > /usr/share/nginx/html/index.html
CMD ["nginx", "-g daemon off;"]
EXPOSE 80