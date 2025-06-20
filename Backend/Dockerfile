FROM node:18

WORKDIR /app

COPY package*.json ./
RUN npm install

COPY . .

# Create uploads directory inside container
RUN mkdir -p uploads

EXPOSE 3032

CMD ["node", "server.js"]

