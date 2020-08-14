# Imagen original a descargar
FROM ubuntu:18.04

# Autor 
MAINTAINER luirro777

# Actualizar la lista de paquetes
RUN apt-get update

# Instalar apache
RUN apt-get install -y apache2 && apt-get clean

# Exponer el puerto 80
EXPOSE 80

# Comando a lanzar cuando se levante un contenedor
CMD apachectl -D FOREGROUND
