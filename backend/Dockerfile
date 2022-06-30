FROM node:12-alpine3.14
WORKDIR /backend
COPY package.json ./
RUN npm install
COPY . .
CMD ["node","app.js"]
EXPOSE 8000
