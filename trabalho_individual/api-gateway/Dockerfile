#See https://aka.ms/containerfastmode to understand how Visual Studio uses this Dockerfile to build your images for faster debugging.

FROM node:16
WORKDIR /api-gateway
COPY package.json /api-gateway/package.json
RUN yarn install
EXPOSE 7000
CMD yarn watch