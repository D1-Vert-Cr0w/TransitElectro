FROM node:alpine as build

COPY pacage.json pacage-lock.json
RUN npm install
COPY . .

EXPOSE 5000
CMD ["node","server.js"]