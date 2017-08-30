下载地址：
https://wenku.baidu.com/view/8aa6762aa8956bec0975e3cd.html?qq-pf-to=pcqq.c2c


index.php 是所有位置
index2.php 是省|市|区

主要是使用sublime Text 3的正则查找和替换

核心正则是：

1.(区|县|省|市|州|旗|盟|单位|岛|域|\(市\))$

2.((.*)0000|(.*)00).*

3.(.*)(00")(.*)

4.(00")
