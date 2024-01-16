FROM node:14

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

ENV MONGODB_USERNAME=root

ENV MONGODB_PASSWORD=secret

EXPOSE 80

CMD [ "node", "app.js" ]