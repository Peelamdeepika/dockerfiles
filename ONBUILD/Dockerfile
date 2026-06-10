FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.htmml
ONBUILD COPY index.htm/usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]