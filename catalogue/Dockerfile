FROM node:20.0
WORKDIR /app
COPY package.json .
COPY *.js .
RUN npm install
CMD ["node", "server.js"]