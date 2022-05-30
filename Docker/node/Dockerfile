FROM node:10
WORKDIR /app
COPY package.json /app
RUN npm install
COPY ./src /app
CMD node app.js
EXPOSE 1050