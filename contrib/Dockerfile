# This file is used to add the nightly Dgraph binaries and assets to Dgraph base
# image.

# This gets built as part of release.sh. Must be run from /tmp/build, with the linux binaries
# already built and placed there.

FROM ubuntu:latest
MAINTAINER Dgraph Labs <contact@dgraph.io>

ADD linux /usr/local/bin

EXPOSE 8080
EXPOSE 9080

RUN mkdir /dgraph
WORKDIR /dgraph

CMD ["dgraph"] # Shows the dgraph version and commands available.
