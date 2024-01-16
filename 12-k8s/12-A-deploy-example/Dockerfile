FROM amd64/node:17-alpine

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

EXPOSE 8080

CMD [ "node", "app.js" ]
