FROM node:14
EXPOSE 3000
ADD node_modules.tar.gz .
WORKDIR /app
COPY . .
CMD [ "npm", "start" ]
