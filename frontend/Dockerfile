FROM node:16-slim

WORKDIR /app

COPY . /app

EXPOSE 3000

RUN npm i

RUN npm run build && npm install -g serve

CMD serve -s build
