FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/testpage/index.html
COPY index.html /usr/share/testpage/index.html
CMD ["nginx", "-g", "daemon off;"]