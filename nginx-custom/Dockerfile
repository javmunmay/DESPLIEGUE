# Usamos una imagen base que ya tiene Apache y PHP instalados
FROM nginx:alpine

#Copiamos el archivo index a la carpeta donde Apache busca archivos
COPY index.html /usr/share/nginx/html

#Exponemos el puerto 80 para que el servidor web sea accesible
EXPOSE 8081