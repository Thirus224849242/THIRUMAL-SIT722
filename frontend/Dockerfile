# Use lightweight Nginx
FROM nginx:alpine

# Set working directory
WORKDIR /usr/share/nginx/html

# Copy all frontend static files (HTML, CSS, JS) into Nginx html folder
COPY . .

# Expose port 80
EXPOSE 80

# Run Nginx in foreground
CMD ["nginx", "-g", "daemon off;"]
