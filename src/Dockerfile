FROM node:current-slim

WORKDIR /usr/src/app
COPY . .
RUN npm install

EXPOSE 3001
USER 1001
CMD [ "npm", "run", "console" ]