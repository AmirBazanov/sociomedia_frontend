FROM node:16-alpine

WORKDIR /API

COPY . .

RUN npm install
RUN npm install -g nodemon

EXPOSE 3001

CMD ["npm", "start"]