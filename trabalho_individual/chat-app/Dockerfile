#See https://aka.ms/containerfastmode to understand how Visual Studio uses this Dockerfile to build your images for faster debugging.

FROM node:16
WORKDIR /chat-app
COPY package.json /chat-app/package.json
RUN yarn install
EXPOSE 7001
CMD yarn watch