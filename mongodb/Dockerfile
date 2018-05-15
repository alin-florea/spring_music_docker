# MongoDB image with host-based data volume

FROM mongo:latest

MAINTAINER Alin Florea <alin.i.florea@gmail.com>
ENV REFRESHED_AT 2018-05-15

VOLUME ["/data/db"]
WORKDIR /data
CMD ["mongod", "--smallfiles"]
