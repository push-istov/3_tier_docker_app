FROM node
WORKDIR /app
COPY . .
ENV MONGO_DB_USERNAME=admin
ENV MONGO_DB_PWD=push372
RUN npm install
EXPOSE 3000
CMD [ "node", "server.js" ]