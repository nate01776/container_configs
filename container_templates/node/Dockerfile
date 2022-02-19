FROM node:7.7.2-alpine

WORKDIR ~/Code/docker_scripts/npm_template/run

COPY ./build/package.json .
RUN npm install --quiet

COPY ./build .