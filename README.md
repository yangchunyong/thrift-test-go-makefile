thrift for go 安装的时候，go的test是使用的code.google.com的mock，对于国内的同志来说需要
翻墙，重新修改了下其中的makefile，使其指向github.com/golang/mock

Installation
------------

    cp ./Makefile   thirft-0.9.2/test/go/
    cd thirft-0.9.2&&make&&make install

my environment
--------------

*Debian GNU/Linux 7.1 (wheezy)
*go 1.5.1
*automake 1.14 （自己下载编译的,thrift-0.9.2用的1.14）
*thirft-0.9.2
