FROM node:12.13
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY ./app .
EXPOSE 8080
CMD ["npm", "run", "serve"]