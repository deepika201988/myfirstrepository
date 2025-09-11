FROM ubuntu:latest

WORKDIR /reactapp

# RUN mkdir /reactapp
# RUN cd /reactapp

COPY . .

RUN apt update && apt install npm -y

RUN npm install

RUN npm audit fix --force

RUN npm install postcss@^8.4.31 --save

# reactpp folder
# data copy host to container
# apt update
# apt install npm -y
# npm install
# npm start

CMD [ "npm", "start" ]

