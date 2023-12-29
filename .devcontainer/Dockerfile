FROM node:20.10.0

# node may come with an older version of npm. Ensure we have a specific npm.
RUN npm install -g npm@10.2.3


################################################################################
# Install prerequisites
RUN apt-get update
RUN apt-get install -y \
    lsb-release \
    curl