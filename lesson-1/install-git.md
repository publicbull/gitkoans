# Installing Git
Go to [git website](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) or [download](https://git-scm.com/downloads)


## Intalling on Linux
Install on Fedora:
```
$ sudo yum install git-all
```
Intall on Debian-based distribution like Ubuntu:
```
$ sudo apt-get install git-all
```

## Intalling on Mac
Step 1: Got to git website to [download](http://git-scm.com/download/mac)
Step 2: Install from the binary installer


## Installing on Windows
Step 1: Got to git website to [download](http://git-scm.com/download/win)
Step 2: Install from the binary installer


## Installing from source
Install on Fedora:
```
$ sudo yum install dh-autoreconf curl-devel expat-devel gettext-devel \
  openssl-devel perl-devel zlib-devel

$ sudo yum install asciidoc xmlto docbook2X getopt

$ sudo ln -s /usr/bin/db2x_docbook2texi /usr/bin/docbook2x-texi

$ tar -zxf git-2.0.0.tar.gz
$ cd git-2.0.0
$ make configure
$ ./configure --prefix=/usr
$ make all doc info
$ sudo make install install-doc install-html install-info
```
Intall on Debian-based distribution like Ubuntu:
```
$ sudo apt-get install dh-autoreconf libcurl4-gnutls-dev libexpat1-dev \
  gettext libz-dev libssl-dev

$ sudo apt-get install asciidoc xmlto docbook2x getopt

$ sudo ln -s /usr/bin/db2x_docbook2texi /usr/bin/docbook2x-texi

$ tar -zxf git-2.0.0.tar.gz
$ cd git-2.0.0
$ make configure
$ ./configure --prefix=/usr
$ make all doc info
$ sudo make install install-doc install-html install-info


```