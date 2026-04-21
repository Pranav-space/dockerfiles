FROM lamalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://raw.githubusercontent.com/Pranav-space/dockerfiles/refs/heads/main/README.md /usr/share/nginx/html/index.html
CMD ["nginx","-g","damon off;"]