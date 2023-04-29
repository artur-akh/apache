**Путь нахождения конфиг файла:**<br>
```bash
/etc/apache2/httpd.conf
/etc/apache2/apache2.conf
/etc/httpd/httpd.conf
/etc/httpd/conf/httpd.conf
```
**Путь файла index.html по умолчанию:**<br>
```bash
 /var/www/html
```
**Проверка синтаксиса:**<br>
```bash
sudo httpd -t
apachectl configtest 
```
**SSL:**<br>
```bash
sudo yum install httpd mod_ssl 
/etc/httpd/conf.d/ssl.conf 
```
