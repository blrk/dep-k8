FROM nginx:1.21

# Remove the default Nginx configuration
RUN rm /etc/nginx/conf.d/default.conf

# Copy the Nginx configuration from your ConfigMap
COPY nginx.conf /etc/nginx/conf.d/

EXPOSE 80
