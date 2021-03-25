FROM node:14.16.0

WORKDIR /frontend

ENV PATH /app/node_modules/.bin:$PATH

COPY ./code .

RUN npm install

EXPOSE 3000
