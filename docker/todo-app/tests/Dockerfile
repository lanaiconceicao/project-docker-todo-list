FROM mjgargani/puppeteer:trybe1.0
WORKDIR /
ADD node_modules.tar.gz ./
# descompactar o arquivo:
CMD ["tar", "-vzxf", "node_modules.tar.gz"]
COPY . ./Dockerfile
ENTRYPOINT ["npm", "test"]
