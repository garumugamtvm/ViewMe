FROM node:18
RUN mkdir -p /opt/app
WORKDIR /opt/app
COPY package.json package-lock.json .
RUN npm install
COPY / .
EXPOSE 4000
CMD [ "npm", "start"]
