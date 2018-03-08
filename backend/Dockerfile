FROM node:latest

RUN mkdir -p /backend
WORKDIR /backend
COPY . /backend

ADD package.json /backend/
RUN npm install 

ADD . /backend/

EXPOSE 9000

CMD ["npm", "start"]
