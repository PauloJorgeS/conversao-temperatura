 FROM node:19.4.0
 WORKDIR /app
 COPY package.json yarn.lock ./
 RUN yarn
 COPY . .
 EXPOSE 8080
 CMD ["node","server.js"]

