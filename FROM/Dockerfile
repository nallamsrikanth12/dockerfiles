FROM almalinux:9
RUN dnf install nginx -y 
LABEL Name="srikanth"\
      Role="devops engineer"\
      duration="full time"
EXPOSE  80
ENV  app="github" \
    Name="srikanth" \
    build="dockerhub"
run rm -rf /usr/share/nginx/html/index.html
ADD sample-1.tar /tmp/
CMD [ "nginx","-g","daemon off;" ]
