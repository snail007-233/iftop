安装前需要已经安装好基本的编译所需的环境，比如make、gcc、autoconf等。

安装iftop还需要安装libpcap和libcurses。

CentOS上安装所需依赖包：

yum install flex byacc  libpcap ncurses ncurses-devel libpcap-devel

Debian上安装所需依赖包：

apt-get install flex byacc  libpcap0.8 libncurses5


下载和编译安装: 

wget https://github.com/snail007/iftop/blob/master/iftop-1.0pre4.tar.gz?raw=true
 
tar zxfv iftop-1.0pre4.tar.gz\?raw\=true
 
cd iftop-1.0pre4
 
./configure
 
make && make install
