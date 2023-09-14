FROM node:14.14.0-alpine
USER root:root
WORKDIR "/app"

COPY ./package.json ./
RUN npm install

COPY . .

CMD ["npm", "run", "start"]