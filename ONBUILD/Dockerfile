FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/ngnix/html/index.html
ONBUILD COPY index.html /usr/share/html/nginx/index.html
CMD ["nginx","-g","daemon off;"]