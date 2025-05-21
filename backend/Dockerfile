FROM node:20

WORKDIR /app

COPY ./ ./

RUN npm i -g @nestjs/cli && npm install && npm run build

CMD ["npm", "start"]
