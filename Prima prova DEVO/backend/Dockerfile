FROM node:14

WORKDIR /backend

COPY package.json .

RUN npm install express body-parser pg querystring

CMD ["node", "start"]
