FROM ubuntu:latest

WORKDIR /reactapp

# RUN mkdir /reactapp
# RUN cd /reactapp

COPY . .

RUN apt update && apt install npm -y

RUN npm install && npm update

#RUN npm audit fix --force

#RUN npm install postcss@^8.4.31 --save

RUN npm install react-scripts@latest

# reactpp folder
# data copy host to container
# apt update
# apt install npm -y
# npm install
# npm start

CMD [ "npm", "start" ]

