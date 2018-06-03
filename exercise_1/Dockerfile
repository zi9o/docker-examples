FROM node:6.14-alpine

LABEL maintainer "Zakaria Elfakhry <dev.zakariaelfakhry@gmail.com>"

LABEL name="node_example_1"
LABEL version="0.1"

WORKDIR /opt/

COPY ./app/package.json package.json

RUN npm install

COPY ./app /opt/

EXPOSE 3000

CMD [ "npm","start" ]