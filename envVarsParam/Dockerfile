FROM node:11-alpine
VOLUME /path/to/dir
ENV diameter=10.0
COPY compute.js .
CMD node compute.js

# docker build -t area .
# docker run --rm -e diameter=100 area