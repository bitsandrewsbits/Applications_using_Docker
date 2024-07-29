# base image, which using for future building image

FROM node:15.14-alpine

WORKDIR /app

EXPOSE 3000

COPY package.json package-lock.json ./

RUN npm install --silient

COPY . ./

# command to start process within container
CMD ["npm", "start"]
