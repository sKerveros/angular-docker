# Use node 20
FROM node:20-alpine

RUN npm install -g @angular/cli analytics off

WORKDIR /angular-app

RUN apk add git
RUN apk add openssh

RUN ng analytics disable --global
EXPOSE 4200
