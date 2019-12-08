FROM node
WORKDIR /home/app
COPY package*.json ./
COPY app.js ./
RUN npm install
RUN npm audit fix
EXPOSE 3000
CMD [ "node", "app.js" ]