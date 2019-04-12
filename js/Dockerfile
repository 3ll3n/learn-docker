FROM node:11.9.0
ADD . /
RUN npm ci 
EXPOSE 3000
ENTRYPOINT ["node", "server.js"]