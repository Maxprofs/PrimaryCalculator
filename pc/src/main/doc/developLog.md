#开发记录
***
>以前的记录丢了，就从今天开始吧

>***
>2016/10/4

>>上午，修改了数据库操作类

>>下午，完成用户的注册以及登陆

>>晚间，进行下一个模块的设计与准备工作。

>>> 1.数据库的表的设计，数据的准备

>>> 2.界面的设计，功能的完成

>2016/10/5 解决数据加载问题

>>在内部解决问题的时候出现的是数据分割的问题

>>一次性记载需要在一个缓冲区中加载多次，但是鉴于数据量小

>>因此，初始缓冲区设置为 char[1024]， 并且一次能够全部加载完毕

>>以上的方式理解错误，字符数量可能超过1024

>>因此需要反复读取，注意对于文件的格式有相应的要求：文件的最后一行应该有且仅有一个换行符

>>数据准备完成 2016/10/5
>***

>2016/10/5 界面设计

