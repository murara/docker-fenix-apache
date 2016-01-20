FROM httpd:2.4

# Habilita módulos
RUN a2enmod rewrite \
 && a2enmod cache \
 && a2enmod cache_disk \
 && a2enmod expires
