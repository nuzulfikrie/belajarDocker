FROM node:alpine
RUN echo "we  are using alpine linux as base"
RUN echo "..copy to ./app"
COPY . /app
WORKDIR /app
RUN echo "running node app.js"
CMD node app.js