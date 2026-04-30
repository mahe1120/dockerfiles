FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/testpage/index.html
ADD https://raw.githubusercontent.com/mahe1120/dockerfiles/refs/heads/main/FROM/Dockerfile /usr/share/testpage/index.html
RUN chmod +r /usr/share/testpage/index.html
ADD sample-1.tar /tmp/
CMD ["nginx", "-g", "daemon off;"]