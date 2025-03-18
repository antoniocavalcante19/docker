# Usa a imagem oficial do Node.js
FROM node:14

# Define o diretório de trabalho no container
WORKDIR /app


COPY package*.json ./


RUN npm install


COPY . .

# Expõe a porta que o app vai rodar
EXPOSE 3000

# Comando para rodar o app
CMD ["npm", "start"]
