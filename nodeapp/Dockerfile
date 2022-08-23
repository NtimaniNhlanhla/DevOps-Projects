FROM node:14
WORKDIR /usr/add
COPY package.json .
RUN npm install
COPY . .
EXPOSE 8080
CMD [ "node", "app.js" ]