FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /use/share/nginx/html/index.html
ONBUILD COPY index.html /use/share/nginx/html/index.html
CMD  ["nginx", "-g", "daemon off;"]
