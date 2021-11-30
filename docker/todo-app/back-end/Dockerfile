FROM node:14-alpine AS todobackend
ADD node_modules.tar.gz .
CMD tar -vzxf node_modules.tar.gz
COPY . .
ENTRYPOINT npm start
EXPOSE 3001