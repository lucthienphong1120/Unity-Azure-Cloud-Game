FROM nginx:alpine
COPY nginx.conf /etc/nginx/conf.d/default.conf
COPY build/WebGL/WebGL /usr/share/nginx/html
CMD ["nginx", "-g", "daemon off;"]
