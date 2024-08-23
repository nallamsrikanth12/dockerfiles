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
ADD https://raw.githubusercontent.com/daws-78s/notes/main/session-01.txt /tmp/srikanth.txt /tmp/srikanth.txt
CMD [ "sleep", "200"]
