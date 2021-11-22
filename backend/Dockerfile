FROM node:14

WORKDIR /usr/src/app

COPY . .
RUN npm install

EXPOSE 25000
CMD [ "node", "index.js" ]