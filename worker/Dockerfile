FROM node
WORKDIR /worker
COPY . .
RUN npm install
ENV MULT=true
ENV ADD=true

CMD ["node","main.js"]

EXPOSE "3000"