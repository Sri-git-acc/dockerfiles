FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://iucn.org/sites/default/files/styles/article_image/public/2022-07/3_monarch-butterfly_-joe-schelling_compressed-for-web.jpg?h=1c9b88c9&itok=RS8WZSQA /usr/share/nginx/html/index.html
RUN chmod +r /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]