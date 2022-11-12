FROM node:14-alpine
WORKDIR /todo-app/back-end
EXPOSE 3000
ADD node_modules.tar.gz .
COPY . .
CMD [ "npm", "start" ]
