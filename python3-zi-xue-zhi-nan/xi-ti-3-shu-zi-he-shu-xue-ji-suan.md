## 除了会写，必须会念的几个数学表达：

* plus 加号
* minus 减号
* / slash 斜杠 除法
* \* asterisk 星号 乘法
* % percent 百分号 模除
* &lt; less-than 小于号
* &gt; greater-than 大于号
* &lt;= less-than-equal 小于等于号
* &gt;= greater-than-equal 大于等于号

**负数读作negative**

运算的两种形式：1. 运算结果  2. 比较结果  True or False

```
# -*- coding: utf-8 -*-
print "I will now count my chickens:"
print "Hens", 25 + 30 / 6  #输出母鸡的计算结果
print "Roosters", 100 - 25 * 3 % 4 #输出公鸡的计算结果
print "Now I will count the eggs:"#输出内容
print 3 + 2 + 1 - 5 + 4 % 2 - 1 / 4 + 6 #计算
print "Is it true that 3 + 2 < 5 - 7?" # 输出内容
print 3 + 2 < 5 - 7 #打印结果
print "What is 3 + 2?", 3 + 2 #输出内容 和运算结果
print "What is 5 - 7?", 5 - 7 #输出内容 和运算结果
print "Oh, that's why it's False." 
print "How about some more."
print "Is it greater?", 5 > -2 #输出比较结果
print "Is it greater or equal?", 5 >= -2 #输出比较结果
print "Is it less or equal?", 5 <= -2 #输出比较结果 true or false
```

问题：除不尽怎么办,可以引用python的 精确除功能，保存到小数点后的10位

```
# -*- coding: utf-8 -*-
from __future__ import division # 两个下划线
print 100/3

33.3333333333
```

什么是floating number ?A floating point number is a number that contains a decimal point. These numbers are floating point numbers 4.5, 767.43, -89.342343, -67.8988893



`print(0.55+0.3)`



结果是0.8500000000000001  ，因为在浮点计算的时候，会先把0.55和0.3转化成二进制数





#### 百分号%怎么运算？

它的表达是A除B的余数 除尽的话是就是0  除不尽就是它的余数

```
>>> print 5%3
2
>>> print 3%3
0
```

```
>>> print (5+3)*7
56
>>> print 5+3*7
26
```

#### 运算顺序怎么？



