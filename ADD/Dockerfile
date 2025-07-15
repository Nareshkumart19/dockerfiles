FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://raw.githubusercontent.com/Nareshkumart19/roboshop11/refs/heads/main/allservers.sh  /usr/share/nginx/html/index.html
RUN chmod +r    /usr/share/nginx/html/index.html
CMD  ["nginx", "-g", "daemon off;"]


#COPY index.html  /usr/share/nginx/html/index.html




