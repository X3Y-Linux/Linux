http://man.linuxde.net/sed




### lsb_release命令
LSB是Linux Standard Base的缩写，lsb_release命令用来显示LSB和特定版本的相关信息。如果使用该命令时不带参数，则默认加上-v参数。

+ -v 显示版本信息。
+ -i 显示发行版的id。
+ -d 显示该发行版的描述信息。
+ -r 显示当前系统是发行版的具体版本号。
+ -c 发行版代号。
+ -a 显示上面的所有信息。 、
+ -h 显示帮助信息。




sudo du -sh *
du -sh .[!.]* * | sort -hr

### df命令


### curl命令：
`curl`

+ 下载单个文件，默认将输出打印到标准输出中(STDOUT)中：

  `curl http://www.centos.org`

+ 通过-o/-O选项保存下载的文件到指定的文件中：

  `curl -o mygettext.html http://www.gnu.org/software/gettext/manual/gettext.html`

+ 通过-L选项进行重定向：
  默认情况下CURL不会发送HTTP Location headers(重定向).当一个被请求页面移动到另一个站点时，会发送一个HTTP Loaction header作为请求，然后将请求重定向到新的地址上。

    `curl -L http://www.google.com`：让curl使用地址重定向，此时会查询google.com.hk站点


### wget命令：
`wget`:wget(选项)(参数)

wget命令用来从指定的URL下载文件。wget非常稳定，它在带宽很窄的情况下和不稳定网络中有很强的适应性，如果是由于网络的原因下载失败，wget会不断的尝试，直到整个文件下载完毕。如果是服务器打断下载过程，它会再次联到服务器上从停止的地方继续下载。这对从那些限定了链接时间的服务器上下载大文件非常有用。
[http://man.linuxde.net/wget](http://man.linuxde.net/wget)
