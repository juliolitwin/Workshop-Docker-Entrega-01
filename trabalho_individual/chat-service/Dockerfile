#See https://aka.ms/containerfastmode to understand how Visual Studio uses this Dockerfile to build your images for faster debugging.

FROM node:16
WORKDIR /chat-service
COPY package.json /chat-service/package.json
RUN yarn install
EXPOSE 7100
CMD yarn watch