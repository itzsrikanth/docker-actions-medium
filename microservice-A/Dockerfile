FROM node:12.16.2-alpine3.11
RUN mkdir /microservice-A
WORKDIR /microservice-A
ADD . .
RUN npm i
CMD ["node", "app.js"]
