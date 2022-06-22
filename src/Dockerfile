FROM node:current-slim

WORKDIR /usr/src/app
COPY . .
RUN npm install

EXPOSE 3001

RUN groupadd -r swuser -g 433 && \
useradd -u 431 -r -g swuser -d /usr/src/app/ -s /sbin/nologin -c "Docker image user" swuser && \
chown -R swuser:swuser /usr/src/app/

CMD [ "npm", "run", "console" ]