# Use the official NGINX base image
FROM nginx

# Copy custom NGINX configuration (optional)
# COPY nginx.conf /etc/nginx/nginx.conf

# Copy your static website files to the default NGINX public folder
# (optional - use if you're serving static HTML)
COPY app/index.html /usr/share/nginx/html/index.html


# Expose port 80
EXPOSE 80

# Start NGINX (default CMD already does this, so this line is optional)
CMD ["nginx", "-g", "daemon off;"]
