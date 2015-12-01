安装前需要已经安装好基本的编译所需的环境，比如make、gcc、autoconf等。

安装iftop还需要安装libpcap和libcurses。

CentOS上安装所需依赖包：

yum install flex byacc  libpcap ncurses ncurses-devel libpcap-devel

Debian上安装所需依赖包：

apt-get install flex byacc  libpcap0.8 libncurses5


下载: 

wget http://www.ex-parrot.com/pdw/iftop/download/iftop-0.17.tar.gz
 
tar zxvf iftop-0.17.tar.gz
 
cd iftop-0.17
 
./configure
 
make && make install
