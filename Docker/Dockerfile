# Dockerfile to setup nginx

# from which image
FROM nginx

# what to copy into the container from localhost - index.html
COPY index.html /usr/share/nginx/html/

# port 80
EXPOSE 80

# CMD specific instructions
CMD ["nginx", "-g", "daemon off;"]