FROM node:20-alpine 
# start a linux OS with node pre-installed

WORKDIR /app
# inside container store the codes in this app directory

COPY package*.json ./

RUN npm install

COPY . .
# copy rest of the files from the project

EXPOSE 5000

CMD [ "node", "server.js" ]