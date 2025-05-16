FROM node:20.19.2-bullseye-slim


WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .

EXPOSE 8080

CMD [ "npm", "run", "start"]
