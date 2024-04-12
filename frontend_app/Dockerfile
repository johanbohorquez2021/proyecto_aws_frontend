# Para el frontend
FROM nginx:alpine

# Actualiza los repositorios e instala net-tools
RUN apt-get update && apt-get install -y net-tools curl

# Copiar el contenido del frontend
COPY . /usr/share/nginx/html

# Establecer la dirección IP del frontend como una variable de entorno
ENV FRONTEND_IP=52.52.10.204