# Commande-Online.fr SAS NGINX DOCKER
  
Need to be plugged with a PHP-FPM docker on port 9000 named phalcon-fpm

CORS enabled for the API

Based on (https://github.com/jprjr/docker-arch-php/blob/master/Dockerfile)

## Notes

To run the PHP-FPM module, php files needs to be placed on the FPM docker in /usr/share/php5-fpm/public  
Mount /usr/share/nginx/html to get the content of your website on the NGINX server