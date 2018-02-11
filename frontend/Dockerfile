# weatherapp frontend Dockerfile
FROM node:8.9.4

WORKDIR /weatherapp_frontend

COPY node_modules /weatherapp_frontend/node_modules
COPY package.json /weatherapp_frontend/package.json
COPY src /weatherapp_frontend/src
COPY webpack.config.js /weatherapp_frontend/webpack.config.js

EXPOSE 8000

CMD ["npm", "start"]