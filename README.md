��װǰ��Ҫ�Ѿ���װ�û����ı�������Ļ���������make��gcc��autoconf�ȡ�

��װiftop����Ҫ��װlibpcap��libcurses��

CentOS�ϰ�װ������������

yum install flex byacc  libpcap ncurses ncurses-devel libpcap-devel

Debian�ϰ�װ������������

apt-get install flex byacc  libpcap0.8 libncurses5


����: 

wget http://www.ex-parrot.com/pdw/iftop/download/iftop-0.17.tar.gz
 
tar zxvf iftop-0.17.tar.gz
 
cd iftop-0.17
 
./configure
 
make && make install
