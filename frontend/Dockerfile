FROM node:14.17.3-buster

WORKDIR /app

COPY package.json package.json 
COPY package-lock.json package-lock.json 

RUN npm ci --production
#RUN npm install

COPY . .

