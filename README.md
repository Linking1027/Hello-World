# one simple example ues python
table = [1,2,3,4,5,6,7,8]
#实现table间隔输出
#first
for xm in table:
    if xm%2 == 1:
        print(xm, end=' | ')
#second
for xm in range(table[0],len(table),2):
    print(xm)
#third
bb = table[0:len(table):2]
print(bb)

#可以看出，第三种方式更加简洁
