# Use an existing docker image as base.
FROM alpine
# Download and install dependencies.
RUN apk add --update redis

RUN apk add --update gcc # it might use cache of image.
# Tell image what to do when deployed in a container.
CMD ["redis-server"]
