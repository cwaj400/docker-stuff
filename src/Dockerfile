FROM node:12
#cd into here. Docker will install dependencies then cache them.
WORKDIR /Dockerfiles
COPY package*.json ./

RUN npm install

COPY . .

ENV PORT=8080

EXPOSE 8080

CMD [ "npm", "start" ]
