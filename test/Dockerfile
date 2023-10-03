FROM node:lts

WORKDIR /api

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 3000

CMD [ "npm", "run", "dev" ]