FROM nginx:latest

COPY ./nginx/conf.d/default.conf /etc/nginx/conf.d/default.conf

COPY . /var/www/html/public

WORKDIR /var/www/html/public
RUN chown -R www-data:www-data /var/www/html/public