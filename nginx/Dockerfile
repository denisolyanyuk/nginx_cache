FROM nginx:latest
COPY --chown=nginx:nginx nginx.conf /etc/nginx/conf.d/default.conf
RUN mkdir "/home/nginx_cache"
COPY 1.png /home/1.png
COPY 2.png /home/2.png

CMD ["nginx", "-g", "daemon off;"]
