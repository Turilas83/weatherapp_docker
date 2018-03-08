FROM node:latest

RUN mkdir -p /frontend
WORKDIR /frontend
COPY . /frontend

ADD package.json /frontend/
RUN npm install 

ADD . /frontend/

EXPOSE 9000

CMD ["npm", "start"]
