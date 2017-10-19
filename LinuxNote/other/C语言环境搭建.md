1、配置GCC

其实刚装好的系统中已经有GCC了，但是这个GCC什么文件都不能编译，因为没有一些必须的头文件，所以要安装build-essential这个软件包，安装了这个包会自动安装上g++,libc6-dev,linux-libc-dev,libstdc++6-4.1-dev等一些必须的软件和头文件的库。

先打开终端，输入命令：
sudo apt-get install build-essential    
