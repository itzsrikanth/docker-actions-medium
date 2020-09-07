FROM node:10.22.0-stretch
RUN mkdir /microservice-A
WORKDIR /microservice-A
ADD admin-tools .
RUN npm i
CMD ["node", "app.js"]
