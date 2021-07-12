FROM node
WORKDIR /planner
COPY . .
RUN npm install
ENV TASKS=4


CMD ["node","main.js"] 

EXPOSE "3000"


