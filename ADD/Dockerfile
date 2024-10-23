FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://www.free-css.com/free-css-templates /usr/share/nginx/html/index.html
CMD ["nginx","-g","daemon off;"]