![输入图片说明](/imgs/2024-09-23/pu4gBZPnMUJVlPbQ.png)
![输入图片说明](/imgs/2024-09-23/WCJWEUps1kly2Toh.png)
其实this就是为了在用构造器时，形参的名字可以跟属性的名字一样，比如这里就是public Dog(String name,int age)，但是名字一样的话形参就跟属性混淆了，所以引出this，跟python的self一样,**this.name=name,this.age=age**
这个this，代表当前**对象**,用了this，**就可以跟形参区分出来了**。

<font size=5 color=red>this 其实等价于对象本身，就是自己，不同对象都可以用this来申明自身。哪个对象调用，this就代表哪个对象。
