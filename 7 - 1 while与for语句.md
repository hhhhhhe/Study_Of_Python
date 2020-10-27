- 1、while循环语法
while 条件 :
  xxx
  xxx
else
  xxx
  xxx
注：else的使用与if-else中的功能是一样的

- 2、for循环
主要是用来遍历/循环序列或者集合、字典的
for target_list in expression_list:
  xxx
  xxx
   
注：target_list是列表中的某一个元素

打印出a中所有的元素
a = [['a','b','c'],(1,2,3)]
for x in a :
  for y in x:
    print(y,end = '')
else :
  print("fruit is gone")

注：end默认是/n，这样结果显示的一列数据，改成''则一行显示
else：是在for循环后进行执行


- 循环10次,0-9,从0开始到什么数字，range(0,10,2) 则是0，2，4，6，8
for x in range(0,10):
  print(x)

- 取a列表中偶数下标的数据
b = a[0:len(a):2]
print(b)

