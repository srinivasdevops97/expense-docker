FROM nginx
COPY code /usr/share/nginx/html
# Removing the default site configuration so it doesn't conflict
RUN rm -rf /etc/nginx/conf.d/default.conf
# Overwrite the global nginx.conf with our nginx.conf file
COPY nginx.conf /etc/nginx/nginx.conf