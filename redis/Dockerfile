# Specify a base image
FROM alpine

# Create the working directory
WORKDIR /usr/app

# Install redis in Alpine
RUN apk add --update redis

# Start the redis-server
CMD [ "redis-server" ]