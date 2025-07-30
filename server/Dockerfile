# Imagen base
FROM node:18

# Crear directorio de trabajo
WORKDIR /app

# Copiar archivos
COPY package*.json ./
RUN npm install
COPY . .

# Exponer el puerto (asegúrate de que tu servidor use este)
EXPOSE 3000

# Comando para iniciar la app
CMD ["node", "server.js"]
