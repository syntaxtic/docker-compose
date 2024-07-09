FROM node:18-alpine

COPY ./app ./app
WORKDIR /app

RUN npm ci && npm cache clean --force

EXPOSE 3000

CMD ["npm", "run", "dev"]
