# 2022.03.09记录

# 1.代码中途断了，怎么继续跑：

![](https://github.com/yyy-psc/23.0310-notes/blob/main/23.0309/1.jpg)

在后面的default里设置路径


![](https://github.com/yyy-psc/23.0310-notes/blob/main/23.0309/2.jpg)

把none改成第几个epoch


# 2.跑验证集时，放入训练后的最好的模型

![](https://github.com/yyy-psc/23.0310-notes/blob/main/23.0309/3.jpg)

在后面的default放入模型的位置信息。


# 3.选择显卡和用几张显卡：

![](https://github.com/yyy-psc/23.0310-notes/blob/main/23.0309/4.jpg)

或者

![](https://github.com/yyy-psc/23.0310-notes/blob/main/23.0309/5.jpg)

（这里制定）

若遇到分布式的：

![](https://github.com/yyy-psc/23.0310-notes/blob/main/23.0309/6.jpg)

这边要的--nproc_per_node=2要和pycharm里面的对应

![](https://github.com/yyy-psc/23.0310-notes/blob/main/23.0309/7.jpg)


4.跑代码步骤：

一般是先跑训练再跑验证。

![](https://github.com/yyy-psc/23.0310-notes/blob/main/23.0309/8.jpg)

即这块在程序里面的parser.add_argumenmt里改好

![](https://github.com/yyy-psc/23.0310-notes/blob/main/23.0309/9.jpg)

前面的是在vnc终端和xshell跑的命令。
