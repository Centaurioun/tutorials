FROM node:14.21.2 
ENV NODE_ENV=production 
WORKDIR /app 
COPY ["package.json", "package-lock.json*", "./"] 
RUN npm install --production 
COPY . . 
CMD [ "node", "server.js" ]