FROM node:12-alpine3.14
WORKDIR /frontend
COPY package.json ./
RUN npm install
#RUN npm ci && npm cache clean --force
COPY . .
CMD ["node","app.js"]
EXPOSE 5000
