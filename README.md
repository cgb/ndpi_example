nDPI example
============

An example of use of the nDPI library

# Installation
The first step is download and compile the nDPI library:
```bash
cd ndpi_exmaple
svn co https://svn.ntop.org/svn/ntop/trunk/nDPI
cd nDPI
./configure –with-pic
make
cd ..
```
The second and last step is to compile ndpiex:
```bash
make
```

# Usage
./ndpiex -f file.pcap