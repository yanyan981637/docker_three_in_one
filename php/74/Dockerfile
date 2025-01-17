FROM bitnami/php-fpm:7.4.33

# 確保 /var/log 目錄存在並設置權限
RUN mkdir -p /var/log \
    && chown -R www-data:www-data /var/log \
    && chmod -R 755 /var/log
