FROM node:14

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

EXPOSE 80

# VOLUME [ "/app/node_modules" ] # the same as adding enonimous volume -v /app/node_modules

CMD [ "node", "server.js" ]