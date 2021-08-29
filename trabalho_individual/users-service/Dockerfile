#See https://aka.ms/containerfastmode to understand how Visual Studio uses this Dockerfile to build your images for faster debugging.

FROM node:16
WORKDIR /users-service
COPY package.json /users-service/package.json
RUN yarn install
EXPOSE 7101
CMD yarn watch