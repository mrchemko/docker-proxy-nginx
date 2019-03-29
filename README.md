# docker-nginx-proxy

## Nginx сейчас обслуживает:

1. control.delfin.by
2. cloud.delfin.by

## Примечания

1. Получение ssl сертификата

        sudo certbot --rsa-key-size 4096 --nginx

2. Удаление сертификата

	certbot revoke --cert-path /etc/letsencrypt/live/CERTNAME/cert.pem — удаляет информацию с серверов letsenrypt
	certbot delete --cert-name example.com — удаляет сертификаты и все симлинки на локальном сервере






