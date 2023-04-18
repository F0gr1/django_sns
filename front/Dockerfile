FROM node:16.2.0
 
WORKDIR /app
RUN npm install -g @vue/cli
RUN npm init
ADD ./package.json /app/package.json
RUN npm install
ADD ./start.sh /app/start.sh
