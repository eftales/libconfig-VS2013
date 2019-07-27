# 前言
libconfig原工程文件不可以在vs2013下编译运行，我修改了一些由于版本造成的问题，使其能够运行在vs2013上。
# 打开方式
右键libconfig_vs2008.sln，使用vs2013打开
# 如何在自己的vs2013工程中调用这个库
1. 将vs2013安装目录下的bin lib 文件夹加入path
![](https://i.imgur.com/xKj4Yd7.png)
2. 将using_libconfig文件夹下的dll lib h文件放入vs2013安装目录下的 bin lib include文件夹
![](https://i.imgur.com/A2pW6My.png)
3. 用vs2013打开using_libconfig文件夹下的工程，根据需求修改。