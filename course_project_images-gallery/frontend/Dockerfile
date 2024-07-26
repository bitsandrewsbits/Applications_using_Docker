# base image, which using for future building image

FROM node:22-alpine3.19

WORKDIR /app

EXPOSE 3000

COPY package.json package-lock.json ./

RUN npm install --silient

COPY . ./

# command to start process within container
CMD ['npm', 'start']
