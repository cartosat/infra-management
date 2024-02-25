# Fetching the latest nginx image
FROM nginx

# Copy SSL certificates
COPY certs/vsw.digital/certificate_fi.crt /etc/ssl/vsw.digital/certificate_fi.crt
COPY certs/vsw.digital/private.key /etc/ssl/vsw.digital/private.key

COPY certs/portfolio.vsw.digital/certificate_fi.crt /etc/ssl/portfolio.vsw.digital/certificate_fi.crt
COPY certs/portfolio.vsw.digital/private.key /etc/ssl/portfolio.vsw.digital/private.key

# Coming soon pages
COPY coming_soon/image-coming-soon.png /etc/coming_soon/image-coming-soon.png
COPY coming_soon/coming-soon.html /etc/coming_soon/coming-soon.html

# Copy custom Nginx configuration file
COPY default.conf /etc/nginx/conf.d/default.conf
