FROM node:13.5.0

WORKDIR /app

ADD ./src/package.json /app
ADD ./src/yarn.lock /app
RUN npm install

ADD ./src/tsconfig.json /app
ADD ./src/src /app
ADD ./src/public /app

EXPOSE 80
CMD ["npm", "start"]
