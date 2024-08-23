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
COPY index.html  /usr/share/nginx/html/index.html
CMD [ "nginx","-g","daemon off;" ]
