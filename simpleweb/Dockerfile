# Specify a base image
FROM node:14-alpine

# Set working directory inside the container.
WORKDIR /usr/app

#Copy source-files required inside the container.
COPY ./app ./

RUN chown -R node:node /usr/app
# Install the dependencies
RUN npm install

#Default command
CMD ["npm", "start"]
