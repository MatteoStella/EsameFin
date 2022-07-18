FROM node:14

# TODO
WORKDIR /myapp

COPY package*.json .

RUN npm install

COPY . .

EXPOSE 8080

CMD ["node", "backendApp.js"]
