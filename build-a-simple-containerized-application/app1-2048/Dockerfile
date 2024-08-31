# use the lastest nginx image, which is specifically designed for simple web applications where the nginx already installed and configured.
FROM nginx:latest

LABEL maintainer="programmingwong@gmail.com"

COPY 2048 /usr/share/nginx/html

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]
