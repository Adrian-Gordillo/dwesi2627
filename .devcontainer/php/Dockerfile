FROM ubuntu/php:8.5-26.04_edge

COPY index.php /var/www/html/index.php

EXPOSE 80

CMD ["php", "-S", "0.0.0.0:80", "-t", "/var/www/html"]