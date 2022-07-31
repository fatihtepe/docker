FROM node:current-alpine3.15
#FROM - platform=linux/amd64 node:current-alpine3.15
WORKDIR /app
ADD . /app
RUN npm install
#RUN npm install express
EXPOSE 3000
CMD ["npm", "start"]