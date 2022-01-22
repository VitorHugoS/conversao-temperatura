FROM node
WORKDIR /app
COPY package*.json ./
RUN cd /app
RUN npm install
COPY . .
EXPOSE 8080
CMD ["node", "server.js"]