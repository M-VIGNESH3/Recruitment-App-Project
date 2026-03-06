FROM nginx:1.25-alpine
# Copy your static site into the default NGINX root
COPY . /usr/share/nginx/html/
# Expose 80 because that's what NGINX listens on by default
EXPOSE 80
# Let docker run publish 90 externally: docker run -p 90:80
CMD ["nginx", "-g", "daemon off;"]
