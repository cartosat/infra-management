# Fetching the latest nginx image
FROM nginx

# Copy SSL certificates
COPY certs/certificate_fi.crt /etc/ssl/certificate_fi.crt
COPY certs/private.key /etc/ssl/private.key

# Copy custom Nginx configuration file
COPY default.conf /etc/nginx/conf.d/default.conf
