FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://raw.githubusercontent.com/daws-84s/notes/refs/heads/main/session-01.txt  /usr/share/nginx/html/index.html
RUN chmod +r    /usr/share/nginx/html/index.html
CMD  ["nginx", "-g", "daemon off;"]
ADD sample-1.tar  /tmp/

#COPY index.html  /usr/share/nginx/html/index.html




