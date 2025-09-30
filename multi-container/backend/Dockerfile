FROM node

WORKDIR /app

COPY package.json /app

RUN npm install

COPY . /app

EXPOSE 80

ENV MONGO_USERNAME=admin
ENV MONGO_PASSWORD=admin

CMD ["npm", "start"]
