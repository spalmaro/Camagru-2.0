FROM node:10

WORKDIR /app

COPY . .

RUN npm install --quiet
RUN npm install -g nodemon

EXPOSE 3000

CMD ["node", "/app/bin/www"]