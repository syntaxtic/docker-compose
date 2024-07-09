FROM node:18-alpine

RUN npm i -g nodemon

COPY ./app ./app
WORKDIR /app

RUN npm ci && npm cache clean --force

EXPOSE 4000

CMD ["npm", "run", "dev"]
