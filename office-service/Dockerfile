from node:lts-alpine3.10

# Create app directory
WORKDIR /usr/src/app


COPY package*.json ./

RUN npm install

COPY . .

CMD [ "node", "index.js" ]
expose 80
