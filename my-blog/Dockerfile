FROM node

WORKDIR /my-blog

COPY package*.json /my-blog/

RUN npm install

COPY . /my-blog/

EXPOSE 3000
CMD [ "npm", "start"]