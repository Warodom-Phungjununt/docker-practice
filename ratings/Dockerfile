FROM node:14.15.0-alpine3.12

WORKDIR /usr/src/app/

COPY src/ /usr/src/app/

RUN npm install

EXPOSE 8080

CMD ["node", "/usr/src/app/rating.js", "8080"]