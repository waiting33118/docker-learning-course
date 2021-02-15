FROM node:lts

WORKDIR /app

COPY package.json /app

RUN npm i

COPY . /app

RUN ls

EXPOSE 3000

CMD [ "npm" , "start" ]