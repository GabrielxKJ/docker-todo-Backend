FROM node:14-alpine AS todobackend
WORKDIR /todo-app
EXPOSE 3001
COPY . . 
ADD node_modules.tar.gz ./
ENTRYPOINT [ "npm, start" ]