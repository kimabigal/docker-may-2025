FROM node:18

WORKDIR /usr/src/app

COPY package.json .

RUN npm install 

COPY . .

ENV PORT=3001 \
    DB=hello \
    DBUSER=kaizen \
    DBPASS=Kaizen123! \
    DBHOST=34.60.37.241 \
    DBPORT=3306


EXPOSE 3001

CMD ["npm", "start"]


