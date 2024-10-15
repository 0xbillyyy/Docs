FROM php:8.2-fpm
WORKDIR /var/www/html
RUN docker-php-ext-install mysqli

#FROM php:8.2-fpm

# Mengatur direktori kerja
#WORKDIR /var/www/html

# Memperbarui package list dan menginstal paket yang diperlukan
#RUN apt-get update && \
#    apt-get install nano -y && \
#    docker-php-ext-install mysqli && \
#    apt-get clean
#    rm -rf /var/lib/apt/lists/*

# (Opsional) Salin file atau konfigurasi lain ke dalam container
# COPY ./src /var/www/html
