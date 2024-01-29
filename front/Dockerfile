# Per crear una imatge: 
# amb el servidor NGINX per servir els fitxers estàtics de front
# Exposa el port 80


# Per crear la imatge: docker build -t server_nginx . 
# Per executar el contenidor: docker run -p 8080:8080 -d server_nginx
# Per veure els logs: docker logs <container_id>
# O directament executar-lo en mode interactiu (-it enlloc de  -d)) : 
# docker run -it -p 80:80 server_nginx

FROM node:latest

# Establecemos el directorio de trabajo en /app
WORKDIR /app

# Instalamos las dependencias
RUN npm install

# Comando para ejecutar la aplicación
CMD ["npm", "run", "dev"]
