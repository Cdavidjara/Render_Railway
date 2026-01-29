# Usa una imagen oficial de PHP
FROM php:8.0-apache

# Copia los archivos del proyecto al contenedor
COPY Website/ /var/www/html/

# Expone el puerto 80 para acceder a la aplicación
EXPOSE 80

# Inicia Apache en primer plano
CMD ["apache2-foreground"]

