FROM alpine:3.13.5

MAINTAINER nnyimc
LABEL Training Docker

RUN apk update && apk upgrade -a && apk add nodejs-npm

WORKDIR /app
COPY pong.js package.json /app/
RUN npm install && ls -la
COPY . .
EXPOSE 80
CMD ["node", "pong.js"]

