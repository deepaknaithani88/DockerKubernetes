# Use an existing docker image as base
FROM node:alpine

WORKDIR /usr/app

# Download and install a dependency
COPY ./package.json ./
# RUN npm install -g npm@7.8.0
RUN npm install
COPY ./ ./

# Tell the image what to do when it starts
# as a container
CMD ["npm", "start"]
