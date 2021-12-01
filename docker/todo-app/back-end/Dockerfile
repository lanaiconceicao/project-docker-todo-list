FROM node:14-alpine
WORKDIR /
ADD node_modules.tar.gz ./
# descompactar o arquivo:
CMD tar -vzxf node_modules.tar.gz
# COPY .(fonte de onde sai os arquivos) ./Dcokerfile(destino)
COPY . .
EXPOSE 3001
ENTRYPOINT npm start