FROM alpine

RUN apk add -update nodejs nodejs-npm

COPY . /src

WORKDIR /src

RUN npm install

EXPOSE 80

ENTRYPOINT ["node", "./app.js"]