# https://hub.docker.com/repository/docker/chatchanokwsa/app
FROM node:12.18.2-stretch
WORKDIR /app
# Dependencies/Library
COPY package*.json ./
RUN npm install
# Copy all files
COPY . .
EXPOSE 4000
CMD [ "npm", "start" ]