FROM node:18-alpine

WORKDIR /usr/src/app/api

COPY . .

RUN npm i

EXPOSE 3080

CMD ["npm", "run", "dev"]
