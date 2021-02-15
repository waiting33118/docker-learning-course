FROM node:lts

WORKDIR /app

COPY package.json /app

RUN npm i

COPY . /app

RUN ls

EXPOSE 80

CMD [ "npm", "run", "dev" ]