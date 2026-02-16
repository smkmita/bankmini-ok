#aktifkan a2enmod rewrited
#tambahkan skrip ke vhost:
---------------------------
<Directory /var/www/>
            Options Indexes FollowSymLinks
            AllowOverride All
            Require all granted
</Directory>
---------------------------
password admin copas dari db_akuntansi_praktek
