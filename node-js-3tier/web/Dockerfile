FROM node:18

WORKDIR /usr/src/app

COPY package.json .

RUN npm install 

COPY . .

ENV PORT=3000 \
    API_HOST=http://34.123.237.49:3001 

EXPOSE 3000

CMD ["npm", "start"]


