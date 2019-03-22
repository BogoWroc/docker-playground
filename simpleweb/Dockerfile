FROM node:alpine

WORKDIR /usr/app

# copy from to
COPY ./package.json ./
RUN npm install
COPY ./ ./

CMD [ "npm", "start" ]  