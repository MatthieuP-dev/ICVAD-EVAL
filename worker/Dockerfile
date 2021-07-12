FROM node:alpine3.14
WORKDIR /worker
COPY . .
RUN npm install
ENV MULT=true
ENV ADD=true

CMD ["node","main.js"]