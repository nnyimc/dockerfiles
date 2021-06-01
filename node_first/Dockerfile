FROM alpine:3.10
RUN apk add --update nodejs nodejs-npm
WORKDIR /app
COPY package*.json pong.js ./
RUN npm install
COPY . .
EXPOSE 5000
CMD ["npm", "start"] 
