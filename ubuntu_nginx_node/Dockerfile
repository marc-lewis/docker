FROM marclewis/ubuntu_nginx

RUN apt-get update && apt-get install -y \
    curl \
    build-essential
RUN curl -sL https://deb.nodesource.com/setup_6.x -o nodesource_setup.sh
RUN bash nodesource_setup.sh
RUN apt-get update && apt-get install -y nodejs

# if we want to symlink because there may be naming issues with ubuntu node package & nodejs
# CMD ["ln", "-s", "/usr/bin/nodejs", "/usr/bin/node"]

# When running nginx as it's own container
# CMD ["nginx", "-g", "daemon off;"]
