FROM node:20

WORKDIR /app

COPY . /app/

RUN npm i -g @nestjs/cli && npm install && npm run build

CMD ["npm", "start"]
