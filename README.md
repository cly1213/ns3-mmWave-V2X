# ns3-mmWave-V2X
## Reference

https://github.com/nyuwireless-unipd/ns3-mmwave

https://github.com/signetlabdei/millicar

### Install 

Recommend: Ubuntu 18.04

Linux install dependencies

```
sudo apt-get install g++ python3
sudo apt-get install g++ python3 python3-dev pkg-config sqlite3
sudo apt-get install python3-setuptools git
sudo apt-get install qt5-default mercurial
sudo apt-get install gir1.2-goocanvas-2.0 python-gi python-gi-cairo python-pygraphviz python3-gi python3-gi-cairo python3-pygraphviz gir1.2-gtk-3.0 ipython ipython3
sudo apt-get install openmpi-bin openmpi-common openmpi-doc libopenmpi-dev
sudo apt-get install autoconf cvs bzr unrar
sudo apt-get install gdb valgrind
sudo apt-get install uncrustify
sudo apt-get install doxygen graphviz imagemagick
sudo apt-get install texlive texlive-extra-utils texlive-latex-extra texlive-font-utils dvipng latexmk
sudo apt-get install python3-sphinx dia
sudo apt-get install gsl-bin libgsl-dev libgsl23 libgslcblas0
sudo apt-get install tcpdump
sudo apt-get install sqlite sqlite3 libsqlite3-dev
sudo apt-get install libxml2 libxml2-dev
sudo apt-get install cmake libc6-dev libc6-dev-i386 libclang-6.0-dev llvm-6.0-dev automake
sudo apt install python3-pip
sudo pip3 install --upgrade pip
python3 -m pip install --user cxxfilt
sudo apt-get install libgtk-3-dev
sudo apt-get install vtun lxc uml-utilities
sudo apt-get install libboost-signals-dev libboost-filesystem-dev
```

### Install ns-3

```
git clone https://gitlab.com/nsnam/ns-3-allinone.git
cd ns-3-allinone/
./download.py -n ns-3.33
cd ns-3.33/

./waf configure
```

### NetAnim

```
cd ns-3-allinone
cd netanim-3.108
make clean
qmake NetAnim.pro
make

./NetAnim
```
