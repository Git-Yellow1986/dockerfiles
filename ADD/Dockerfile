FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://www.gathertales.com/?gad_source=1&gclid=CjwKCAiApsm7BhBZEiwAvIu2X_k2iDsaFoA4qG5jc072L5zmVybtnTG2YTMBzmoIonV_353pkU2XMRoCgJ4QAvD_BwE  /usr/share/nginx/html/index.html
RUN chmod +x /usr/share/nginx/html/index.html
CMD ["nginx","-g","daemon off;"]
