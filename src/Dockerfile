FROM node:22.11.0-alpine3.19
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . ./
EXPOSE 8080
CMD ["node","server.js"]