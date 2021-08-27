FROM node 

WORKDIR /test-nodeapp-1-task
COPY package.json /.
COPY server.js /.
COPY yarn.lock /.
COPY . .
RUN CI=true
RUN npm install -g npm@7.21.1
#RUN npm install react-scripts

EXPOSE 8080
CMD ["yarn", "start"]
