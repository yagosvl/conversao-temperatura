FROM Node:18.11.0
WORKDIR /temperaturaApp
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 8080
CMD ["node", "server.js"]
