FROM node:alpine

WORKDIR /src

ADD . /src

RUN npm install 

RUN npm run build

CMD node .
