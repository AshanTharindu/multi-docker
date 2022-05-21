FROM node:14.14.0-alpine

WORKDIR "/app"

COPY ./package.json ./

RUN npm instal

COPY . .

CMD [ "npm", "run", "start" ]

