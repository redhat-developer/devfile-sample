FROM node:current-slim

WORKDIR /usr/src/app
COPY . .
RUN npm install

EXPOSE 3000
USER 1001
CMD [ "node", "server.js" ]