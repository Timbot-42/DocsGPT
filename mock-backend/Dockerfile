FROM node:20.19.3-bullseye-slim


WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .

EXPOSE 8080

CMD [ "npm", "run", "start"]
