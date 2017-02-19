FROM ubuntu:16.04

RUN apt-get update && apt-get install -y nginx nano


# Remove the default Nginx configuration file
# RUN rm -v /etc/nginx/nginx.conf

# Copy a configuration file from the current directory
#ADD nginx.conf /etc/nginx/

EXPOSE 80

# if running nginx as a process and we do not want the container to exit
# CMD ["nginx", "-g", "daemon off;"]
