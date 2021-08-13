#Imagem Node
FROM node:12
#Diretório Virtual criado
RUN mkdir /usr/src/app

WORKDIR /usr/src/app 
#Comando nodemon para executar permanente
RUN npm install -g nodemon --quiet

EXPOSE 3000

CMD ["npm", "start"]
