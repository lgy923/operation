1、 查看VMnet8的IP地址

Win+R打开运行窗口，输入cmd进入DOS界面

![img](images/1.png)

输入ifconfig/all查看网络参数信息

![img](images/2.png)

查看VMnet8

![img](images/3.png)

2、配置VMware网络配置，选择“NAT模式”

![img](images/4.png)

3、打开VMware中的Ubuntu系统，“设置”—“网络”—“网络代理”

![img](images/5.png)

 

4、打开windows系统（安装VMware的本机系统）上的shadowsocks，勾选“允许其他设备连入”。

 

 

5、测试一下，可以访问国外网站了

![img](images/6.png)