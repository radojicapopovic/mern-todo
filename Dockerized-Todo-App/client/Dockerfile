FROM node

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

EXPOSE 3000

ENV MONGODB_USERNAME=merntodo123
ENV MONGODB_PASSWORD=merntodo123

CMD [ "npm", "start" ]