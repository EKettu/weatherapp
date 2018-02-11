# weatherapp backend Dockerfile

FROM node:8.9.4

WORKDIR /weatherapp_backend

COPY node_modules /weatherapp_backend/node_modules
COPY package.json /weatherapp_backend/package.json
COPY src /weatherapp_backend/src

EXPOSE 9000

CMD ["npm", "start"]