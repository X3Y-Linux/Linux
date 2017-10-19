


## ps命令
ps命令用于报告当前系统的进程状态。可以搭配kill指令随时中断、删除不必要的程序。ps命令是最基本同时也是非常强大的进程查看命令，使用该命令可以确定有哪些进程正在运行和运行的状态、进程是否结束、进程有没有僵死、哪些进程占用了过多的资源等等，总之大部分信息都是可以通过执行该命令得到的。

`ps -aux|grep nginx`







## netstat命令

[http://man.linuxde.net/netstat]

netstat命令用来打印Linux中网络系统的状态信息，可让你得知整个Linux系统的网络情况。


netstat -atnpl | grep nginx





## pkill命令
pkill命令可以按照进程名杀死进程。pkill和killall应用方法差不多，也是直接杀死运行中的程序；如果您想杀掉单个进程，请用kill来杀掉。

语法：`pkill(选项)(参数)`

来自: http://man.linuxde.net/pkill
