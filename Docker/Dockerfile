FROM nginx:latest
COPY index.html /usr/share/nginx/html/index.html
COPY health.html /usr/share/nginx/html/health.html
COPY status.html /usr/share/nginx/html/status.html
CMD ["/bin/sh", "-c", "nginx && nginx -s reload && tail -f /dev/null"]