FROM node:alpine
WORKDIR '/multi-docker-containers'
COPY ./package.json ./
RUN npm install
COPY . .
CMD ["npm","run","start"]