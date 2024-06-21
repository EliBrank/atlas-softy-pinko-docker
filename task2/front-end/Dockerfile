FROM nginx

COPY softy-pinko-front-end/. /var/www/html/softy-pinko-front-end

COPY softy-pinko-front-end.conf /etc/nginx/conf.d/default.conf

EXPOSE 5252

CMD ["python3","api.py"]
