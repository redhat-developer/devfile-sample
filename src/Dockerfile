FROM node:current-slim

WORKDIR /usr/src/app
COPY . .
RUN npm install

EXPOSE 3001
CMD [ "npm", "run", "console" ]
