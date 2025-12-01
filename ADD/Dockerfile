FROM almalinux:9
RUN dnf install nginx -y 
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://raw.githubusercontent.com/Git-Yellow1986/terraform-expense-infra-dev/refs/heads/main/readMe.MD /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]

