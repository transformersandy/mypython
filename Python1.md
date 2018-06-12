

# time
```
import time
date = time.localtime()		#取得目前的日期時間
year = date[0]
month = date[1]
day = date[2]
day_month = [31, 28, 31, 30, 31, 30, 31, 31, 30, 31, 30, 31]
if year%400==0 or (year%4==0 and year%100!=0):	#判斷是否為閏年
    day_month[1] = 29
if month==1:
    print(day)
else:
    print(sum(day_month[:month-1])+day)

```
# zodiac
```
#!/usr/bin/python
#-*- coding: UTF-8 -*-  # print chinese
print("")
print("西元年代對應到的十二生肖")
print("")
year = eval(input("請輸入你出生的年代: "))
print("")
zodiacYear = year % 12 
if zodiacYear == 0:
    print("monkey===猴子哩")
elif zodiacYear == 1:
    print("rooster雞")
elif zodiacYear == 2:
    print("dog狗狗")
elif zodiacYear == 3:
    print("pig豬豬")
elif zodiacYear == 4: 
    print("rat鼠")
elif zodiacYear == 5: 
    print("ox牛")
elif zodiacYear == 6:
    print("tiger虎虎生威")
elif zodiacYear == 7:
    print("rabbit兔子")
elif zodiacYear == 8:
    print("dragon偉大的龍")
elif zodiacYear == 9:
    print("snake蛇")
elif zodiacYear == 10:
    print("horse馬")
else: 
    print("sheep羊")

```
# ???

```
#!/usr/bin/python
# -*- coding: UTF-8 -*- 
 
for i in range(1,5):
    for j in range(1,5):
        for k in range(1,5):
            if( i != k ) and (i != j) and (j != k):
                print (i,j,k)
               
```
