# Node image
FROM node:latest

# Maintainer
MAINTAINER Rinaldo Rossi <rinaldo.rossi.web@gmail.com>

# Create code directory
RUN mkdir /app

# Set the workdir
WORKDIR /app

# Install the packeges
RUN npm install -g truffle@beta

# Expose port 8080 & 8545
EXPOSE 8080 9545

