FROM node:lts

WORKDIR /app

COPY package.json /app

RUN npm i

COPY . /app

EXPOSE 8000

CMD  [ "npm", "run", "dev" ]