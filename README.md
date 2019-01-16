# oneKeyJDK
一键Java环境部署


批处理命令：一键安装JDK/一键安装JRE和自动配置Java环境变量
安装JDK/安装JRE以及配置java环境变量对于java初学者来说是一件比较头疼的事情，这边分享一个简单的批处理命令，助大家一步完成JDK或者单独安装JRK的需求。

关键步骤：

1.新建一个.txt文档，复制附件一/附件二到文档中；

2.修改文档中的内容：

附件一：start /WAIT jdk-8u141-windows-i586.exe /qn INSTALLDIR=C:\Java\jdk1.8

附件二：start /WAIT jre-8u144-windows-i586.exe /s INSTALLDIR=C:\Java\jre

加红部分修改成你自己下载的JDK名字/JRE名字，注意：文档和软件请放在一个文件夹下

3.将.txt文档后缀修改成.bat后缀；

4.双击运行，最后就安装配置完成了。
