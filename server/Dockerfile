FROM node:18-alpine3.15

WORKDIR /usr/src/app/server
COPY package*.json .
RUN npm install
COPY . .

CMD ["npm", "run", "dev"]
