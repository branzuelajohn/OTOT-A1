FROM nginx

# remove the default nginx configs to avoid conflict

RUN rm /etc/nginx/nginx.conf /etc/nginx/conf.d/default.conf


# copy the nginx config
COPY nginx.conf /etc/nginx/nginx.conf

# Run nginx
CMD ["nginx", "-g", "daemon off;"]