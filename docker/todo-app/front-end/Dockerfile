FROM node:14-alpine
WORKDIR /
ADD node_modules.tar.gz ./
# descompactar o arquivo:
CMD tar -vzxf node_modules.tar.gz
COPY . ./Dockerfile
EXPOSE 3000
ENTRYPOINT npm start
