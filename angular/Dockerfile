FROM node:10 

LABEL maintainer="Julien"

WORKDIR /app

COPY package*.json ./

RUN npm install

COPY . .

RUN npm run build --prod

EXPOSE 80

CMD ["npm", "start"]
