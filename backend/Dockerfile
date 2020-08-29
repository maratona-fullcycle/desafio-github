FROM node:erbium-alpine As development
WORKDIR /usr/src/app
COPY package*.json ./
RUN yarn
COPY . .
RUN yarn test