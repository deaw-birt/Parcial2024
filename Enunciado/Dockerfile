# Dockerfile para PARCIAL DEAW
# A partir de la imagen de Ubuntu 18.04
FROM ubuntu:18.04

# Responsable del fichero
LABEL \
	version="1.0" \
	description="Ubuntu18.04 + Apache2 + PARCIAL" \
	creationDate="XX-XX-XXXX"

# Ejecutamos comandos
RUN \
	apt-get update  \
    (...)

# Copiamos ficheros necesarios
COPY (...) /var/www/html/
(...)

COPY html/privado.html /var/www/html/privado

# Ejecutamos comandos
(...)

# Exponemos puertos
(...)