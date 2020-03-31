FROM node:10-alpine
EXPOSE 3000
COPY . /app
WORKDIR /app
RUN /bin/sh -c 'npm install; npm cache clean --force'
CMD npm start





