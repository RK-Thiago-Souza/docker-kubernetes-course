FROM node:alpine

WORKDIR '/app/redis-app'

COPY package.json .
RUN npm install
COPY . .

CMD ["npm", "start"]