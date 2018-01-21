# python-
贪玩python之初极蛇皮怪
大家好，我是渣渣庆

python两大有序列表：list 与 tuple（元组）
list：list=['渣渣辉','是兄弟就来砍我','渣渣庆']。。定义list用中括号
list.append(['好的，拿刀来','吃我一棒，嘿嘿'])。。调用append()方法
list[-1]。。索引最后一个
list[-1][0]。。。也可以这样查找,有点类似java里的二维数组
list葵花四式：
增/插：见上面的append(),list.insert(1,['怎少得的我','咕添乐'])。。可以插入又一个列表
删：list.pop(4)
改/替换：list[0]='我是渣渣辉'...
查：见上面的索引

获取长度：len(list)
list =['str',123,True]。。多种类型


tuple:
t=(1,)一个元素时要用逗号，定义元组用小括号
最大特点：一旦写下，不可改变，所以没有增和插和删。改/替换只有在有list才能改/替换list的内容
但：
t=(1,2,['a','b'])
t[2][1]='c'
print(t)
(1,2,['a','c'])。。当元组里有list时可以改变list内容，因为tuple的指向还是不变的，变的只是list的指向，tuple指向的list还是当初你的大爷。



总结：tuple比list安全，索引都是[]，调用方法都是()


