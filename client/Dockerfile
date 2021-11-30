FROM node:16.13.0 

WORKDIR /usr/app

COPY package*.json ./

RUN npm install -qy

COPY . .

CMD ["npm", "run", "dev"]

EXPOSE 8000

