FROM nginx:latest

# RUN apt-get update
# RUN apt-get install vim -y

# COPY .docker/nginx/vhost.conf /etc/nginx/sites-enabled/skylabs-portal-vhost.conf
ADD .docker/nginx/vhost.conf /etc/nginx/conf.d/default.conf

# RUN echo "include /etc/nginx/sites-enabled/*.conf;" >> /etc/nginx/conf.d/default.conf
# RUN echo "server_names_hash_bucket_size 64;" >> /etc/nginx/conf.d/default.conf
# RUN echo "client_max_body_size 12M;" >> /etc/nginx/conf.d/default.conf

WORKDIR /var/www/html/source-code