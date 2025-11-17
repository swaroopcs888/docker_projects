# Specify a base image
FROM node:24-alpine

# Work directory
WORKDIR /usr/app


# Install some dependencies
COPY ./package.json ./
RUN npm install
COPY ./ ./

# Default command
CMD ["npm", "start"]

