FROM node:18-alpine

WORKDIR /usr/src/app/ui

COPY package*.json ./

RUN npm i

EXPOSE 3000

CMD ["npm", "start"]
